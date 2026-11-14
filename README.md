# Scam Detector 🔍

### AI-Powered SMS Spam and Suspicious Message Detection

**Hackathon Track:** AI + Finance

## About
Scam Detector is a hybrid AI system that analyses SMS messages to identify spam and suspicious financial messages.

## How It Works
- **TF-IDF:** Converts text into numerical features.
- **Complement Naive Bayes:** Classifies spam-like messages.
- **Security Checks:** Identifies warning signs such as password, PIN and OTP requests.
- **Safety Advice:** Provides warnings when suspicious messages are detected.

## Technology
- Python
- Pandas
- Scikit-learn
- TF-IDF
- Complement Naive Bayes

## Dataset
UCI SMS Spam Collection  
5,572 original messages; 5,169 unique messages after cleaning.

Dataset: https://archive.ics.uci.edu/dataset/228/sms+spam+collection

## Model Results

| Metric | Result |
|---|---:|
| Accuracy | 96.52% |
| Spam Precision | 84% |
| Spam Recall | 89% |
| Spam F1-score | 0.87 |

These results describe the machine-learning model on the held-out test set.

## Limitations
The model uses general English SMS data and may not detect every real-world or region-specific financial scam. It is an educational prototype, not a guarantee of safety.

## Future Improvements
- Pakistani financial scam datasets
- Urdu language support
- Improved detection explanations
- User-friendly web application
