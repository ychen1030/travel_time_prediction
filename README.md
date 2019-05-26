## Travel Time Prediction

##### Yingying Chen
#### UCB-263-2019-5

Given training data on Uber/Lyft trip OD locations, starting time and durations, travel times between two specified locations at a given departure time are estimated. This is the 1st place solution of the in-class Kaggle competition.

This project consists of three main parts:
- Data Understating & Cleaning
- Feature Extraction
- Model & Training

Takeaways:
- Feature engineering is the most important part of the prediction task.
- Complex model is a double-edged sword.
- XGBoost with GPU improved the training speed for ~3 times.
- Prediction query could be handled in real time.