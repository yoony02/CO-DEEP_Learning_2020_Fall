## Co-Deep Learning 2020 Fall

2020년 2학기 성균관대학교 Co-Deep Learning Project 결과물을 올려둔 곳입니다. 
Project 기간이 끝나고 결과물을 다듬어 같은 주제로 iConference 2021의 Workshop으로 열린 <a href = 'https://ai-informetrics.github.io/'>1st Workshop on AI + Informetrics (AII2021)</a>에 참가했습니다.

성균관대학교 학술정보관에서 제공해주신 2015부터 2019년까지의 대출기록을 이용해 도서 개인화 추천 시스템을 구현하고자 하였고, 도서의 정보와 
학생의 정보를 임베딩해서 Embedding based Neural Network에 사용할 수 있도록 하였습니다. 모델링에 대한 자세한 내용은 코드(*.ipynb)와 Workshop에 제출한 Paper를 업로드해두었으니 읽어보시면 됩니다.

다음은 AII2021에 제출한 short paper의 Abstract 입니다.


### **Embedding-based Neural Network Models for Book Recommendation in University Libraries**

> *Recommendation systems have been widely used in various commercial applications for predicting the rating a user may give to an item. 
To encourage students to read more books, personalized book rec- ommendation systems are of great interest in university libraries. 
Because university libraries do not ask students to rate books that they borrowed, book reviews and ratings are not available. 
Without book ratings, implementing personalized book recommendation systems in libraries is a challenging problem. 
In this study, we propose a library book recommen- dation system that uses embedding based neural network models. 
The system uses book metadata and user information as input features and deep learning models were used to create embeddings of the features. 
A multi-class classification model and a multi-label classification model were trained and soft voting was used to integrate the final outcomes. 
The performance of the models was evaluated by 72 university students and the multi-class classification model received 3.4 average points whereas the multi-label classification model scored 3.0 average points in the 5- Point Likert Scale.*


