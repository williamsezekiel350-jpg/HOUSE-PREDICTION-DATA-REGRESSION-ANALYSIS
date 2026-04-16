# HOUSE-PREDICTION-DATA-REGRESSION-ANALYSIS
Linear regression analysis on house prediction dataset
Checking the current notebook state to verify the regression analysis implementation. 

Retrieving Notebook summary.

## Linear Regression Analysis - Complete ✅

The comprehensive linear regression analysis on the Boston Housing dataset (`4) house Prediction Data Set.csv`) has been **fully implemented and executed** in Regression Analysis.ipynb.

### Analysis Components Completed:

**1. Dataset Preparation**
- Loaded 506 samples with 13 features + 1 target variable (MEDV)
- No missing values detected
- All features are numeric

**2. Train/Test Split**
- Training set: 404 samples (80%)
- Testing set: 102 samples (20%)
- Random state: 42 (reproducible)

**3. Linear Regression Model**
- Model: `sklearn.linear_model.LinearRegression`
- Successfully fitted on training data
- Model intercept: **$30,247**

**4. Model Evaluation Metrics**
| Metric | Value |
|--------|-------|
| R-squared | **0.6688** (explains 66.9% of variance) |
| Mean Squared Error | **24.2911** |
| Root Mean Squared Error | **4.9286** ($4,929) |
| Mean Absolute % Error | **16.87%** |

**5. Feature Coefficients (Ranked by Impact)**
- **NOX** (pollution): -17.20 (strongest negative predictor)
- **RM** (rooms): +4.44 (strongest positive predictor)
- **LSTAT** (poverty %): -0.51
- **PTRATIO** (teacher ratio): -0.92
- **DIS** (distance to jobs): -1.45

**6. Visualizations Generated**
- ✅ Actual vs Predicted scatter plot → actual_vs_predicted_housing.png
- ✅ Residual plot → residual_plot_housing.png

All cells have been executed successfully with comprehensive output showing model performance and interpretation.
