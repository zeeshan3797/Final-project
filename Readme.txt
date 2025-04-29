# IoT Botnet Detection Using Machine Learning

This project implements a complete pipeline for detecting botnet attacks in IoT networks using supervised machine learning models. It includes data preprocessing, feature selection, model training with K-Fold cross-validation, hyperparameter tuning, evaluation on unseen data, and performance visualization.

---

## Project Structure

- **data/**: Contains CSV files with labeled traffic samples (benign and various attack types like Mirai, Gafgyt).
- **notebooks/**: Colab notebook with the end-to-end ML pipeline.
- **models/**: Serialize models trained during cross-validation.
- **plots/**: Confusion matrix visualizations and heatmaps.
- **README.md**: Project documentation.

---

## Features

- Feature standardization using `StandardScaler`
- Label encoding for 11-class classification
- K-Fold cross-validation with early stopping
- Multiple classifiers:
  - Random Forest
  - Support Vector Machine 
  - Multi-layer Perceptron 
- Performance metrics:
  - Accuracy, Precision, Recall, F1-score
  - Confusion matrices 
  - Classification reports
- Hyperparameter tuning with `GridSearchCV`

---

## Dataset Description

The dataset is a labeled traffic log representing benign and malicious (attack) IoT activity. Key classes include:

- benign
- mirai_ack
- mirai_scan
- mirai_syn
- mirai_udp
- mirai_udp_plain
- gafgyt_combo
- gafgyt_junk
- gafgyt_scan
- gafgyt_tcp
- gafgyt_udp


## Start

### Clone the Repository and start

