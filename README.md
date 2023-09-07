Malaria Detection Using Deep Learning
Introduction
Problem Definition
The problem at hand is to build an efficient computer vision model to detect malaria in red blood cells. Malaria is a significant and contagious disease that affects a large portion of the global population, and it can be life-threatening if not diagnosed and treated early. Traditional laboratory diagnosis of malaria is time-consuming and relies heavily on human expertise, leading to potential inaccuracies due to inter-observer variability.

Objective
The primary goal is to develop an automated system using Machine Learning (ML) and Deep Learning Algorithms (a subset of Artificial Intelligence) that can accurately detect malaria in red blood cells. The model should be capable of distinguishing between infected (parasitized) red blood cells, containing Plasmodium parasites, and uninfected red blood cells, which could have other impurities.

Key Questions
How can we effectively differentiate between infected and uninfected red blood cells in the images? What features or patterns should the model look for to make accurate classifications? How can we ensure the model's accuracy and reliability in detecting malaria? What are the potential challenges or limitations in using Machine Learning and Deep Learning for this task? Problem Formulation:

Using data science, the objective is to develop a computer vision model that can analyze colored images of red blood cells and classify them as either parasitized (infected with Plasmodium parasites) or uninfected. The model's success will be measured by its ability to provide early and accurate detection of malaria, reducing the dependency on manual inspection and minimizing the risk of misdiagnosis or delayed treatment.

By leveraging Machine Learning and Deep Learning techniques, the model should be able to generalize well to new, unseen data and deliver a high level of accuracy in detecting malaria. This automated system will aid in timely diagnosis and better management of malaria cases, particularly in vulnerable populations like children under 5 years old, who are most susceptible to severe outcomes from the disease. Ultimately, the aim is to contribute to global efforts in reducing the prevalence and impact of malaria on public health.

Data Description
There are a total of 24,958 train and 2,600 test images (colored) that we have taken from microscopic images. These images are of the following categories:

Parasitized: The parasitized cells contain the Plasmodium parasite which causes malaria
Uninfected: The uninfected cells are free of the Plasmodium parasites

Steps to solve the problem
Loading the data.

Data preprocessing.

Spliting data in Train , Evaluation and Test set.

Data Analysis (EDA).

Creating global function for ploting and drawing CM

Base Model: CNN Model

Model 1: CNN Model modified - 2 additional layers

Model 2: CNN Model modified - LeakyReLU and BatchNormalization

Model 3: Data Augmentation - ImageDataGenerator

Model 4: Transfer Learning - VGG16

Evaluations & Obeservations

Saving the best model

Conclusion
