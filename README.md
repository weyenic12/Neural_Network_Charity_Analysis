## Overview of the Analysis
- Our goal was to create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

--------------------------
## Results
- Our target variable is 'IS_SUCCESSFUL' for the model.
- Other variables that are features are:
  - APPLICATION_TYPE—Alphabet Soup application type
  - AFFILIATION—Affiliated sector of industry
  - CLASSIFICATION—Government organization classification
  - USE_CASE—Use case for funding
  - ORGANIZATION—Organization type
  - STATUS—Active status
  - INCOME_AMT—Income classification
  - SPECIAL_CONSIDERATIONS—Special consideration for application
  - ASK_AMT—Funding amount requested
- We are removing EIN and NAME—Identification columns from the data.
- [model_info](https://user-images.githubusercontent.com/80421977/127804022-9b1e9e21-6c1a-444f-b9bb-34c53a7dd38b.PNG)
- Tried to increase the accuracy of the model by increasing the application_count to be higher for our replace_application and I dropped three additional columns in our application_df. However, by doing this it made the model go from 72% accuracy down to 68% accuracy and therefore was unsuccessful.
--------------------------
## Summary
- I attempted a few ways above to make the model more accurate from our 72% to over 75% and was unsuccessful in my attempts. I believe if I continued to work with the model, I may be able to slightly increase the accuracy a few percent more.
