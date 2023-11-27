# Breast Cancer Classification Analysis

This repository contains a comprehensive analysis of breast cancer classification using machine learning techniques. The analysis involves Decision Trees, SVM, and Logistic Regression models.

## Data Source

The Breast Cancer Wisconsin (Diagnostic) Dataset used in this analysis is available [here](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).


## Overview

The project aims to predict breast cancer diagnosis (malignant or benign) using the Breast Cancer Wisconsin (Diagnostic) Dataset from scikit-learn. Various models and techniques are employed for classification and analysis.

## Files

- `breast_cancer_classification.ipynb`: Jupyter Notebook containing the detailed analysis and code implementation.
- `README.md`: Provides an overview of the project.
- Any additional files or resources used in the analysis.

## Project Structure

1. **Data Loading and Preprocessing**: Loading the dataset, splitting data into training and testing sets.
2. **Decision Tree Model Analysis**: Training Decision Tree models with varying depths and criteria, analyzing accuracy trends.
3. **Selected Decision Tree Model**: Identifying important features and using a selected Decision Tree model.
4. **SVM Model Analysis**: Training Support Vector Machine models and visualizing decision boundaries.
5. **Confusion Matrix and Logistic Regression Analysis**: Analyzing Logistic Regression model performance and creating ROC curves.
6. **Feature Selection and Hyperparameter Tuning**: Utilizing RFE and GridSearchCV for feature selection and model tuning.
7. **Retraining Models on Selected Features**: Retraining SVM and Logistic Regression on selected features.

## Setup and Installation

To run the notebook, install the required libraries:
pip install scikit-learn matplotlib pandas mlxtend seaborn


## Usage

- Open the Jupyter Notebook `breast_cancer_classification.ipynb` for a step-by-step analysis.
- Execute the cells to run the code and view the results.

## Contribution

Contributions are welcome! If you have suggestions or improvements, feel free to create a pull request.

---

This breast cancer classification analysis provides insights into machine learning models' performance and techniques for diagnosis prediction.

