# Exoplanet Habitability Prediction

This project, showcased in the Jupyter notebook `exoplanet-habitability-prediction (2).ipynb`, involves the development of a machine learning model to assess the habitability of exoplanets. Utilizing large-scale astrophysical data, the model predicts the likelihood that a planet outside our solar system could potentially support life.

## Overview

The aim of this project is to use data science techniques to analyze and predict which exoplanets might be habitable. This involves processing and interpreting complex data sets to identify key features that might indicate a planet's ability to support life.

## Technologies Used

- **Python**: For all programming needs.
- **Pandas & NumPy**: For data manipulation and numerical operations.
- **Scikit-Learn**: For implementing machine learning models.
- **Matplotlib & SciPy**: For data visualization and scientific computing.

## Dataset

The dataset includes various parameters of planets collected from multiple space observatories. This includes planetary size, orbit, temperature, and atmospheric conditions, among other factors.

## Features

- **Data Processing**: Implementation of data cleaning and feature scaling to enhance the accuracy of the model.
- **Predictive Modeling**: Use of statistical and machine learning techniques to predict habitability.
- **Model Evaluation**: Assessment of the model performance with a focus on accuracy and the reduction of false positives.

## Models Used

- **Logistic Regression**: To predict binary outcomes of habitability.
- **Random Forest**: To handle the classification based on a multitude of factors and ensure a robust model with high accuracy.

## Results

The model achieved a 98% accuracy rate in predicting the habitability of exoplanets, significantly reducing false positives and optimizing resource allocation for further telescopic observations.

## Installation

To set up this project locally, you can follow these steps:

```bash
git clone https://github.com/your-username/exoplanet-habitability-prediction.git
cd exoplanet-habitability-prediction
pip install -r requirements.txt
