# Adaptive Physics-Based Feature Engineering for Machine Learning-Assisted Alloy Discovery

This repository contains the code and dataset used in the study:  
**"A Novel Adaptive Physics-based Feature Engineering Approach for Machine Learning-assisted Alloy Discovery"**  
by **Yasaman J. Soofi, Yijia Gu, and Jinling Liu.**

The study introduces an **adaptive physics-based feature engineering method** that improves machine learning predictions for alloy properties by leveraging domain-specific knowledge. By decomposing categorical features into meaningful subunits, this approach outperforms traditional encoding methods like one-hot encoding, achieving **enhanced prediction accuracy (R² up to 0.94)**.

[Read the published paper here.](https://www.sciencedirect.com/science/article/pii/S0927025623002422)

---

## Overview

This repository demonstrates how **physics-informed feature engineering** can significantly enhance the performance of machine learning models in alloy discovery. The adaptive encoding method integrates domain-specific physics into categorical feature representations, leading to improved model robustness and interpretability.

Key contributions include:
- Improved prediction accuracy for material properties (R² up to 0.94) compared to one-hot encoding.
- Validation using advanced statistical techniques such as **Student’s t-test** (P-values < 1e-10), **Leave-One-Out Cross-Validation (LOOCV)**, and random seed testing.
- Application of **Random Forest regression and classification models** for mechanical and technological property prediction.

---

## Code Files

### Statistical Analysis
1. **`correlation_heatmap.ipynb`**  
   - Performs Spearman correlation analysis and generates heatmaps to visualize variable relationships.

2. **`feature_importance.ipynb`**  
   - Analyzes feature importance for mechanical and technological properties and generates top-10 feature importance plots.

### Predictive Modeling
3. **`20221025-Hu_Dataset_prediction.ipynb`**  
   - Implements Random Forest regression models to predict alloy properties for 100 different random seeds using the dataset from Hu et al.

4. **`100seeds_mechanical.ipynb`**  
   - Implements Random Forest regression models for mechanical property prediction across 100 random seeds.

5. **`100seeds_technological.ipynb`**  
   - Implements Random Forest classification models for technological property prediction across 100 random seeds.

---

## Key Features
- **Physics-Informed Feature Engineering**: Decomposes categorical features into domain-specific subunits to enhance model performance and interpretability.
- **Supervised Learning Models**: Random Forest regression and classification for predicting material properties.
- **Statistical Validation**: Ensures reliability with LOOCV, random seed testing, and Student’s t-test.
- **Visualization**: Correlation heatmaps and feature importance plots to highlight key variables.

---

## Technologies Used
- **Programming Languages**: Python (pandas, numpy, scikit-learn, Matplotlib).  
- **Machine Learning Techniques**: Random Forest Regression, Random Forest Classification.  
- **Statistical Methods**: Spearman correlation, LOOCV, Student’s t-test.  
- **Dataset**: Includes processed data from Hu et al. and other alloy studies.

---

## Related Work

For additional insights into machine learning-assisted alloy design, explore my earlier project:  
[ML-Assisted Alloy Design Using Wrought Aluminum Alloys](https://github.com/yasamanjs/ML-assisted-alloy-design-using-wrought-aluminum-alloys).

---

## Citation

If you use this repository in your work, please cite:  
**"A Novel Adaptive Physics-based Feature Engineering Approach for Machine Learning-assisted Alloy Discovery"**  
by **Yasaman J. Soofi, Yijia Gu, and Jinling Liu**.  
[DOI Link](https://www.sciencedirect.com/science/article/pii/S0927025623002422)

---

Feel free to open issues or contribute to the repository. Feedback and suggestions are always welcome!
