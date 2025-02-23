# Enhancing Elderly Healthcare Utilization through Machine Learning
## **Proposal Overview**
This project explores a machine learning-driven approach to predict and enhance elderly healthcare utilization. While existing models predict health risks, they often fail to ensure timely checkups and doctor visits. This study integrates wearable sensor data, demographic factors, and medical history to develop a predictive model that identifies individuals at risk of missing routine checkups and provides personalized intervention strategies. Using Regression Discontinuity (RD) design, we also assess the causal impact of Medicare eligibility and social support on healthcare engagement.

## **Background**
Regular healthcare checkups are crucial for preventive care and chronic disease management in older adults. However, many elderly individuals fail to seek timely medical attention due to mobility issues, cognitive decline, financial constraints, or lack of social support. Traditional healthcare prediction models focus on risk assessment, but few studies explore proactive intervention strategies.

Wearable sensor data (e.g., step count, heart rate variability, sleep patterns) provides real-time insights into elderly health behaviors, offering an opportunity to predict healthcare disengagement. By combining predictive modeling and causal inference, this research aims to develop data-driven strategies that encourage timely medical checkups and preventive healthcare engagement.

## **Research Objective**
### **1. Healthcare Engagement Prediction**
Can machine learning models accurately predict whether an elderly individual is at risk of missing routine doctor checkups based on wearable data, demographic factors, and medical history?

### **2. Causal Analysis**
Evaluate whether Medicare eligibility (at age 65) or social support (caregiver involvement) causally influences elderly healthcare utilization.

## **Methodology**
### **1. Machine Learning for Explanation**
We use pre-trained NLP models (BERT, GPT) to analyze elderly individuals' healthcare-related text data from doctor-patient conversations, health forums, and self-reported symptoms.

- Sentiment analysis assesses attitudes toward healthcare engagement.
- Text classification identifies barriers affecting checkups.
- Topic modeling uncovers key themes influencing medical decisions.
- Saliency maps and attention visualizations provide insights into critical language patterns, improving model interpretability.

### **2. Machine Learning for Prediction**
A Random Forest classifier is used to predict whether an elderly individual is at risk of missing routine checkups, leveraging wearable sensor data and medical history.
By identifying high-risk individuals, this model enables early intervention through personalized reminders and telehealth outreach.

### **3. Causal Inference Using Machine Learning**
To assess whether Medicare eligibility (financial assistance) or social support (caregiver involvement) increases healthcare engagement, we apply Regression Discontinuity (RD) design.

- Running Variable: Age (Medicare eligibility threshold = 65).
- Treatment Group: Individuals 65+ (eligible for Medicare).
- Control Group: Individuals 60-64 (not yet eligible).
- Outcome Variable: Annual doctor visits & checkup adherence.
- Instrumental Variable: Caregiver presence, to measure its impact on checkup likelihood.
By comparing healthcare behaviors before and after the Medicare cutoff, we estimate its causal impact on medical engagement. These insights guide policy improvements for elderly healthcare accessibility.

## **Evaluation**
### **1. Explanation (NLP Analysis Results)**
Healthcare engagement sentiment trends reveal that negative attitudes toward doctor visits are linked to low checkup adherence.
Key topics include financial barriers, mobility challenges, and trust in telehealth services.

### **2. Prediction (Random Forest Model Performance)**

| Model            | Accuracy / R² | Key Insights |
|-----------------|--------------|-------------|
| **Random Forest**   | 82%          | Identifies elderly at risk of missing checkups. |
| **Neural Network**  | 86%          | Captures complex wearable-healthcare relationships. |
| **NLP Sentiment**   | N/A          | Detects behavioral reluctance to seek care. |


### **3. Causal Inference (Regression Discontinuity Analysis Results)**
- Medicare Eligibility (Age 65) → +3.02 annual doctor visits (statistically significant).
- Social Support (Caregiver Involvement) → Higher checkup adherence.
- Policy Impact: Financial aid & social support networks significantly increase healthcare engagement.

## **Poster**

![Gray and White Simplified Professional Portrait University Research Poster](https://github.com/user-attachments/assets/887ac69a-bb77-49fb-8ff1-4c37cfb2df58)


## **Future Work**
- Expand wearable data integration: Include blood pressure, glucose monitoring, and cognitive decline markers.
- Real-world deployment: Develop a mobile reminder system for at-risk individuals.
- Policy applications: Collaborate with healthcare providers to improve elderly healthcare accessibility.

## **Conclusion & Contribution**

- Bridges ML & Healthcare Accessibility: First-of-its-kind AI-driven intervention system that predicts and prevents missed checkups.
- Bridges Prediction & Policy Insights: Identifies financial & social factors influencing healthcare engagement.
- Bridges Wearable Tech & Causal Inference: Provides a data-driven approach to elderly preventive healthcare.

This research moves beyond passive health monitoring to create an actionable, AI-powered framework that improves elderly healthcare outcomes. 

## **Acknowledgments**
We would like to thank researchers contributing to wearable-based healthcare prediction and causal inference in aging studies for providing foundational datasets and methodologies.




