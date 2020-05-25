# Marketing Muse

Using data science and machine learning to who figure out who is more likely to click on an ad.

## Summary:

The idea was to extract information from this kaggle dataset (https://www.kaggle.com/fayomi/advertising)

The approach taken to solve this problem proceeded as follows:

- Importing and cleaning the data
    - Removed null values, duplicates, and 
    - Removed observations with unrealistic values (Age of 999 years, etc)
- Data Visualization
    - Highlited feature distributions: subsetting into groups who clicked on the ad and groups who didn't
    - Uncovered bimodal distributions and behaviors of target groups
    - Visualized correlations to target feature
- Feature engineering
    - Engineered datetime features to bucket weekends, weekdays, and peak shopping periods
    - Investigated and removed both counrty and city features due to high cardinality and minimal insight
    - Scaled and normalized numerical features
- Machine Learning
    - Used Logistic regression and grid search to achieve:
    - **Accuracy of 96%**
    - **Precision of 99%**
    - **Recall of 93%**
    - **F1-score of 98%**
    
    - Highlighted feature importance using random forest



