# Lending Club Case Study
> Helping **consumer finance company** to make a decision for loan approval based on the applicant’s profile.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Analysis of Loan Applicants info and make decision for Loan approval
- There are two type of risks involved in lending money like
    -   If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
    -   If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
- The Above 2 risks are to be solved using data and identify the default borrowers and reduce loss by rejecting application
- Loan.csv file is the dataset that is being used.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Data Analysis Results
- From Univariant Analysis the Beneficial Variable we got are as fallows:
    - home_ownership: defaulters rate varies
    - term_in_months: defaulters rate decreases
    - Grade: defaulters rate decreases(B>C>D>E>A>F>G), A has to be verified.
    - sub_grade: defaulters rate decreases(B5-G5) 
    - Purpose: defaulters rate is varies 
    - dti_range: defaulters rate increases
    - Int_range: defaulters rate decreases
    - installment_range: defaulters rate increases
    - monthly_inc_range: defaulters rate 
    - Loan_amnt: We can observe some outliers and the first quartile is bigger than third quartile for loan amount which means most of the defaulters clients are from      first quartile
- From Bivariant Analysis related variable are:
    * loan_amnt_range and purpose: default ratio increases for every purpose wrt loan_amnt_range
    * grade and purpose: default ratio increases for every purpose w.r.t grade
    * loan_amnt_range and term_in_months: default ratio increases for every purpose w.r.t loan_amnt_range
    * monthly_inc_range and purpose: default ratio increases for every purpose w.r.t monthly_inc_range 
    * term vs purpose: default ration increases for every purpose w.r.t term
    * Instalment_range vs purpose: default ratio increases for every purpose w.r.t installment except for small business 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.9.7
- numpy - version 1.22.3
- pandas - version 3.5.1

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusion
-Through Heat map we observed that there is not that much co-related with each other for numerical variable.
-We can consider the univariant variable and bivariant analysis variable for guessing the Defaulters.
-We can also divide loan according to bivariant variables for guessing Defaulters.


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad
- This project was based on [Case study problem statement from Upgrad](https://learn.upgrad.com).


## Contact
Created by [@yuvarajdr](https://github.com/yuvarajdr) - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
