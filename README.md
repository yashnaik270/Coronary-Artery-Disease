# CORONARY ARTERY DISEASE

HOW CAN YOU USE THIS PROJECT AND MAKE CHNAGES:
1. ADD CAD11.ipnb TO COLAB/JUPYTER THEN ADD CAD.CSV FILE AND ANALYSE
2. THEN AUGMENT THAT CSV FILE YOU WLL GET CAD_AUGMENTED.CSV
3. AROUND 10000 PATIENTS YOU WILL GET 5000 CAD AND 5000 NON-CAD
4. THEN TRAIN THE MODEL AND TEST IT
5. NOW DOWNLOAD THE CAD_BLOCKAGE.ipynb AND THEN USE BLOACKAGE DATA WITH THAT FILE AND YOU WILL GET SEVERITY.
6. MAKLE A UI AND INTEGRATE THE BEST MODEL ADN YOUR DONE :)

   
🚨 Machine Learning Meets Cardiology: CAD Prediction & Severity Estimation 🫀📊

Over the past few weeks, I had the opportunity to work on a data-driven healthcare challenge: predicting Coronary Artery Disease (CAD) and estimating its severity (blockage %) using clinical data and machine learning — a potential game-changer for early diagnosis and triage.

💡 Project Objective
To build a dual-stage predictive system that:
1️⃣ Classifies whether a patient has CAD (Yes/No)
2️⃣ Estimates the arterial blockage percentage to assess severity and guide medical decision-making.

🛠️ Tech Stack & Workflow

Language: Python

Libraries: Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn

Models Used:

Classification: XGBoost Classifier

Regression: XGBoost Regressor

Evaluation: Accuracy, MAE, RMSE, Confusion Matrix

Data: 2000 patient records (original + synthetically balanced)

📊 Key Features Used

Age, Sex, Chest Pain Type, Resting BP, Cholesterol

Fasting Blood Sugar, Resting ECG, Max Heart Rate

Exercise-induced Angina, ST Depression (Oldpeak), ST Slope

Plus 14 additional engineered features

🧪 Model Evaluation Strategy
To ensure robustness, I applied a 6-iteration validation approach with shuffled training splits. Each round trained on a different 1000-sample chunk, ensuring reliability and generalization. Logged accuracy, confusion matrices, and blockage prediction error metrics.

📈 Outcome Highlights

✅ CAD Classification:

High accuracy across all iterations

Reliable predictions on unseen patients
🔹 "Patient #9 — Predicted: CAD | Actual: CAD"
🔹 "Patient #25 — Predicted: No CAD | Actual: No CAD"

📏 Severity Estimation (XGBoost Regressor):

Predicts arterial blockage % (0–100%)

Auto-labels as:

🔵 Mild (<40%)

🟡 Moderate (40–70%)

🔴 Severe (>70%)

Example:
🔹 "Blockage: 82.4% — Severity: Severe — Immediate attention required."

🧑‍💻 Team & Mentorship

This project was a collaborative effort with my incredibly skilled teammates:
🎯 Harshal Patil, Shivshankar Kasapknor, and Ashok Nadar — your contributions, insights, and code reviews were instrumental in shaping this solution.

Special gratitude to our mentor, Dr. Ravindra Chaudhary, for his unwavering guidance, clinical insights, and support throughout the project. 🙏

🙌 Why This Matters
With cardiovascular disease being the #1 global cause of death, this project demonstrates how ML can assist clinicians in early detection, severity triage, and faster patient turnaround in real-world settings.

🚀 Next Step
Currently building a GUI-based CAD prediction dashboard for real-time hospital use — with risk stratification, medical advice prompts, and auto-generated PDF reports.

📢 Open to feedback, collabs, or deployment discussions from the healthcare + AI ecosystem!

#MachineLearning #HealthcareAI #Cardiology #CADPrediction #XGBoost #Python #SeverityEstimation #ClinicalAI #MedicalInnovation #AIforGood #DataScience #Teamwork #Leadership
