Home Credit - Credit Risk Model Stability (by yisakberhanu)

**Description**

This repository offers code and explanations for the Kaggle competition, "Home Credit - Credit Risk Model Stability." The objective is to develop a model that forecasts loan default risk while prioritizing stability over time.

**Getting Started**

1. **Prerequisites:**
    Ensure you have Python installed on your system. You can check the version by running `python --version` or `python3 --version` in your terminal. Download and install the appropriate version from [https://www.python.org/downloads/](https://www.python.org/downloads/) if needed.
   - **Libraries:** Install the following libraries using `pip`:

     ```bash
     pip install lightgbm numpy pandas polars catboost scikit-learn joblib
     ```

2. **Clone this repository:** Use `git clone https://github.com/yisakberhanu/home-credit-risk-stability.git`


4. **Run the notebooks:**
   - Refer to `data_reading.ipynb` for instructions on downloading and preprocessing the competition data from Kaggle: [https://www.kaggle.com/competitions/home-credit-credit-risk-model-stability/data](https://www.kaggle.com/competitions/home-credit-credit-risk-model-stability/data)
   - Explore `model_training.ipynb` to understand the model building process, including feature engineering and training on the prepared data.
   - Utilize `inference.ipynb` to learn how to use the trained model for making predictions on new data.

**Data**

* The `data` folder within this repository is intended to store the downloaded competition data.

**Models**

* This folder contains scripts for building and evaluating models. The approach might involve techniques like LightGBM or other algorithms suitable for stability-focused tasks. (Provide a brief overview of the specific models used in your notebooks, incorporating insights from the competition evaluation criteria).

**Evaluation**

* The notebooks explain the custom stability metric used in the competition, which combines AUC (Area Under the ROC Curve) with a penalty for performance degradation over time.
* The code calculates the gini score, falling rate, and standard deviation of residuals to assess stability comprehensively.



**Contribution**

* Pull requests are welcome! (if applicable)
* Follow contribution guidelines (link/describe guidelines here).

**License**

* Appach 2.0.

**Authors**

* Yisak Berhanu 

**References**

* Kaggle

