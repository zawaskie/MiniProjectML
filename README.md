# MiniProjectML
**Project description:**.  
This project aims to classify breast cancer data using the K-Nearest Neighbours (KNN) algorithm. The dataset used is the **Breast Cancer Wisconsin Dataset** from **scikit-learn**. The project includes data processing, splitting the dataset into training and test sets, training the KNN model and evaluating its performance using accuracy, precision and recall metrics.

**Project Aims:**.  
1. To build a classification model for breast cancer detection based on available features.  
2. Evaluate the performance of the model using **accuracy**, **precision** and **recall** metrics.  
3. View the **Precision-Recall Curve** as an additional performance analysis.

**Insights:**.  
- KNN with k=5 is used for classification.
- Data is split into **80% for training** and **20% for testing**.
- The **Model Accuracy** is calculated to assess how well the model classifies the data.
- The precision-recall curve is used to understand the trade-off between precision and recall, especially if the dataset has class imbalances.

**Dependencies:**.  
- Pandas for data manipulation.  
- scikit-learn for data handling, preprocessing, KNN model and evaluation metrics.  
- matplotlib.pyplot for visualising the precision-recall curve.

**Advice:**  

1. **Consider the interpretation of the precision-recall curve:** This curve is more useful if the dataset has class imbalances. If the class distribution is balanced, consider also plotting the **ROC curve**.
2. **Experiment with different values of K:** The KNN model is strongly influenced by the `n_neighbours` parameter. Try to explore other values of `k` to find the best performance.
3. **Feature scaling:** KNN is sensitive to feature scaling, so consider normalising or standardising the feature scaling.
