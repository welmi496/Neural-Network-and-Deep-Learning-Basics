# Image Classification with a Feedforward Neural Network on CIFAR-10

## Project Overview
This project implements an image classification assignment using the CIFAR-10 dataset and a feedforward neural network built with TensorFlow/Keras. The notebook includes data loading, visualization, preprocessing, model training, evaluation, confusion matrices, classification reports, and a short deployment discussion.

## Files
- `Image_Classification_CIFAR10_Assignment.ipynb` - main Google Colab notebook
- `Image_Classification_Report.pdf` - short report for submission
- `README.md` - project description and setup instructions

## Dataset
CIFAR-10 contains 60,000 32x32 color images in 10 classes:
- airplane
- automobile
- bird
- cat
- deer
- dog
- frog
- horse
- ship
- truck

## Requirements
Install the required libraries in Google Colab or Python:
```python
!pip install tensorflow scikit-learn matplotlib seaborn pandas numpy
```

## How to Run
1. Open the notebook in Google Colab.
2. Run all cells from top to bottom.
3. Review the generated plots, metrics, classification report, and confusion matrices.
4. Export the notebook to PDF if needed.

## Model Details
The notebook includes:
- a baseline feedforward neural network
- an improved feedforward neural network with additional dense layers, batch normalization, and dropout
- evaluation with accuracy, precision, recall, F1-score, confusion matrix, and classification report

## Submission
Upload the notebook and README to GitHub, then submit the report PDF with your GitHub repository link.
