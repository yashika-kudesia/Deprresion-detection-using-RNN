# Deprresion-detection-using-RNN
This project aims to propose a method for speech-based diagnosis of depression using recurrent neural networks (long short term memory).
Resented a depression detection model based on sequences of audio and text transcriptions. Evaluated long short-term memory (LSTM) model (using the sequences of responses, and without context of the questions). Their findings showed that context-free modelling based on text features performed better than audio features when classifying for a binary outcome (depressed vs. non-depressed). However, audio features were more accurate in determining the multi-class depression score. As expected, the multi-modal model yielded the best performance.
# DATASET
The data will be drawn from the Distress Analysis Interview Corpus (DAIC) (7), that contains clinical interviews designed to support the diagnosis of psychological distress conditions such as anxiety, depression, and post-traumatic stress disorder. These interviews were collected as part of a larger effort to create a computer agent that interviews people and identifies verbal and nonverbal indicators of mental illness (8).
Data collected include audio and video recordings and extensive questionnaire responses; this part of the corpus includes the Wizard-of-Oz interviews, conducted by an animated virtual interviewer called Ellie, controlled by a human interviewer in another room. Data has been transcribed and annotated for a variety of verbal and non-verbal features. This dataset includes 189 sessions of interactions ranging between 7-33min (with an average of 16min). Each session includes transcript of the interaction, participant audio files, and facial features.

# Link for dataset 
https://dcapswoz.ict.usc.edu/
