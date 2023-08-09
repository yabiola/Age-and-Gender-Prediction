**Age Estimation & Gender Classification - Collaborative Project by Adeyinka Abiola and Hongyi Han**

Welcome to our collaborative Age Estimation and Gender Classification project repository. Here, we delve into the captivating realm of deep learning, utilizing the UTKFace dataset. Together, we build and train intricate models that can predict age and classify gender with the precision of modern technology.

**Project Synopsis**

Our project revolves around harnessing the power of deep learning to predict age and classify gender from facial images. The UTKFace dataset forms the bedrock of our exploration, enabling us to test and fine-tune our models. With the support of Google Colab's GPU capabilities, we set out to craft models that replicate human accuracy in gender classification and age estimation.

**Team Collaboration and Contribution**

Our collaboration has been rooted in equal contribution, with both team members dedicating their time and expertise to various aspects of the project. Our synergy and shared responsibilities have led us to this comprehensive analysis and insights.

**Dataset**
A train val folder has been created by choosing a subset (5,000 face images) from the UTKFace dataset. It is a shared google drive folder below.
https://drive.google.com/drive/folders/1UjYRDyo10Fx-Rv91CQl5ZfwF85HiLUX8?usp=sharing

UTKFace dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). The dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity. The images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc. The labels of each image are embedded in the file name, formatted as [age] [gender] [race] [date&time].jpg.

NOTE: We acknowledge that this dataset has some moral issues (e.g., using appearance to tell the gender or race, not considering genders other than female and male), which might upset some people. We don’t consider these moral issues simply because we only use it for machine learning exercise.
However, you MUST consider potential moral issues when using any dataset in your future research or career.

**Project Workflow**

1. **Data Exploration:** We delve into the UTKFace dataset, understanding its nuances, and extracting vital information for our models.

2. **Model Design:** Together, we design two CNN models - one from scratch and another by fine-tuning a pre-trained architecture.

3. **Training and Optimization:** Our training process involves careful parameter tuning and optimization, ensuring our models capture intricate patterns and nuances.

4. **Results and Analysis:** We present our findings, discussing the performance of both models, their strengths, and areas of improvement.

**Deliverables** 

1. **Jupyter Notebook:** We provide a comprehensive Jupyter Notebook (age_gender_submit.ipynb) containing our code, annotations, and model training steps.

2. **Model Outputs:** We share the trained models:
   - Age Gender A.h5: Our custom-designed CNN model trained from scratch.
   - Age Gender B.h5: A pre-trained CNN model fine-tuned on the UTKFace dataset.

3. **Report:** Our in-depth report outlines our project journey:
   - Introduction: Briefly describing our focus on age estimation and gender classification.
   - Our CNN Model: Detailing our personally designed architecture, training strategies, and performance insights.
   - Pre-trained Model: Discussing our experience fine-tuning a pre-trained CNN model and its outcomes.
   - Summary & Discussion: We conclude by comparing our models, reflecting on the essence of this project, and providing space for additional discussions.
