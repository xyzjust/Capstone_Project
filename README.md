# CapstoneProject

#### Build an automatica trading bot by leveraging ML techniques
[*Supporting article on Medium*](https://xyzjust.medium.com/ml-assisted-trading-strategy-dsnd-capstone-project-6859b50c27b1?source=friends_link&sk=7ca253c02fe9f95d21ef9a5a274668b8)

## Motivation

The practice of using machines to provide and follow through with a trading strategy has been done for decades with billions of investments into the technology to facilitate this. Historically, this project could have only been done in a research facility with access to a bloomberg terminal as well as the coding behind it to automatically place trades. However, the rise in crypto-currency as well as crypto-exchanges, facilitated by open source programming languages (e.g. Python) and increase in computing power. All these elements have resulted in the possibilities of doing such a project, with nothing more than a good computer and an internet connection to.

## Result
A mock up of a trading pipeline has successfully been coded up with r2_score of just above 0.3 obtained on XGBoost models. The models successfully executed some trades for December 2020 in the simulation:
![alt text](https://raw.githubusercontent.com/xyzjust/Capstone_Project/main/example_plot.png)

## Dependencies/Packages used

- Python : **3.7.6**
- xgboost  :  **1.3.0.post0**
- scikit-learn  :  **0.23.2**
- pandas  :  **1.1.3**
- numpy  :  **1.19.2**
- matplotlib  :  **3.3.2**


## Important Files

`Capstone_Project.ipynb` -- The Jupyter notebook of which the coding is done in, using standard Python libraries such as pandas, numpy, matplotlib and sklearn etc

`Analysis.ipynb` -- The Jupyter notebook of which the analysis on some of the decisions were done

## Acknowledgments
Binance 1-min dataset, Kaggle: https://www.kaggle.com/jorijnsmit/binance-full-history
