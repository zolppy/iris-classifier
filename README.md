# Iris Dataset Classification with MLP

This project demonstrates the use of a Multi-layer Perceptron (MLP) classifier on the Iris dataset. It includes data preprocessing, hyperparameter tuning with GridSearchCV, model evaluation using metrics like accuracy, precision, recall, F-score, and specificity, and visualization of ROC curves for multi-class classification.

## Features

- **Data Preprocessing**: Standardization of features using `StandardScaler`.
- **Hyperparameter Tuning**: Grid search (`GridSearchCV`) to find optimal MLP parameters.
- **Model Evaluation**: Metrics such as accuracy, precision, recall, F-score, and specificity for each class and overall.
- **Visualization**: ROC curves for multi-class classification.

## Requirements

- Python 3.x.
- Libraries: `scikit-learn`, `matplotlib`, `numpy`.

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/iris-mlp-classification.git
cd iris-mlp-classification
```

2. Run the Jupyter notebook:

```bash
jupyter notebook main.ipynb
```

## Results

The notebook outputs:

- Best hyperparameters from `GridSearchCV`.
- Evaluation metrics for each class and the overall model.
- ROC curves visualizing the performance for each class.

## License

This project is open-source and available under the Creative Commons License.
