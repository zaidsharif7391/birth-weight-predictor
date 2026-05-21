
# Birth Weight Prediction Using Machine Learning

A Machine Learning based web application developed using Flask that predicts the birth weight of a baby based on maternal and pregnancy-related health factors.

---

## Project Overview

This project uses Machine Learning algorithms to predict the birth weight of a child using several input features such as:

- Gestation Period
- Parity
- Mother's Age
- Height
- Weight
- Smoking Habit

The model is trained on historical pregnancy data and deployed through a Flask web application where users can enter values and get predictions instantly.

---

## Features

✅ Machine Learning Prediction Model  
✅ Flask Web Application  
✅ Interactive HTML User Interface  
✅ Real-Time Birth Weight Prediction  
✅ Simple and Clean Design  
✅ Trained Model Deployment  

---

## Technologies Used

- Python
- Flask
- HTML & CSS
- Scikit-Learn
- Pandas
- NumPy
- Jupyter Notebook

---

## Project Structure
birth-weight-predictor/
│
├── app.py
├── model.pkl
├── requirements.txt
├── README.md
├── babies.csv
├── model_training.ipynb
│
├── templates/
│   └── index.html
│
└── .gitignore



## Dataset Information

The dataset contains pregnancy-related attributes used for training the model.

### Input Features

| Feature   | Description                    |
| --------- | ------------------------------ |
| Gestation | Pregnancy duration             |
| Parity    | Number of previous pregnancies |
| Age       | Mother's age                   |
| Height    | Mother's height                |
| Weight    | Mother's weight                |
| Smoke     | Smoking habit                  |

### Target Variable

* Birth Weight

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Selection
5. Model Training
6. Model Evaluation
7. Model Serialization using Pickle
8. Flask Deployment

---

## Installation Guide

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/birth-weight-predictor.git
```

### Step 2: Open Project Folder

```bash
cd birth-weight-predictor
```

### Step 3: Install Dependencies

```bash
pip install -r requirements.txt
```

### Step 4: Run Flask Application

```bash
python app.py
```

---

## Run Application

After running the Flask server, open:

```bash
http://127.0.0.1:5000
```

in your browser.

---

## Web Application Preview

The application allows users to:

* Enter pregnancy-related details
* Submit the form
* Receive predicted birth weight instantly

---

## Model Deployment

The trained machine learning model is stored using:

```python
pickle
```

and loaded in Flask using:

```python
with open("model.pkl", 'rb') as obj:
    model = pickle.load(obj)
```

---

## Future Improvements

* Add advanced ML algorithms
* Improve prediction accuracy
* Deploy on cloud platforms
* Add graphical visualizations
* Improve UI/UX design
* Add user authentication

---

## Applications

This project can be useful for:

* Healthcare Research
* Medical Data Analysis
* Pregnancy Monitoring Systems
* Educational Purposes
* Machine Learning Demonstrations

---

## Author

Zaid Sharif

---

## License

This project is created for educational and academic purposes.

---

```
```
