# CNNPredictor
# Summary
CNNPredictor is a project focused on utilizing convolutional neural networks (CNN) to predict the presence of Covid-19 based on chest x-ray screening images. The project has attuned "Xception" and "MobileNetV2" CNN models to achieve this objective.

# About the Project
In this endeavor, the "Xception" and "MobileNetV2" convolutional neural networks models were fine-tuned to predict whether a patient’s chest x-ray screening images indicated a positive Covid-19 diagnosis. The enhanced version of this project also includes the capability to determine other conditions such as "Pneumonia_bacteria" and "Pheumonia_Virus". The best test accuracy achieved for determining Covid or normal was 99%, and 84% when adding the two additional classes.

# How to Use the App
Run the app.py script to start the Flask application.
Access the application through your web browser.
Input the required data or upload the chest x-ray image.
Click on the "Predict" button to get the prediction. The result will indicate the likelihood of the presence of heart disease based on the provided data.
Uploading User Models
Currently, the application uses a pre-trained model (model.pkl) for predictions. If you wish to use your own model:

# Train your model and save it in the pickle format.
Replace the existing model.pkl in the models directory with your model.
Ensure that the input and output structure of your model matches the application's requirements.
