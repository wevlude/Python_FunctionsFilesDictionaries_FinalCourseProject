# Python_FunctionsFilesDictionaries_FinalCourseProject

Bu proje Michigan Üniversitesi Python Functions, Files, and Dictionaries kursunun final projesidir.Daha fazla bilgi için  https://www.coursera.org/learn/python-functions-files-dictionaries/

Final Project of the course Python Functions, Files, and Dictionaries. This course is part of the Python 3 Programming Specialization offer by University of Michigan in Coursera. You can find more information at https://www.coursera.org/learn/python-functions-files-dictionaries/

# Fonksiyonlar

1. def strip_punctuation(strWord):

Bu fonksiyon parametre olarak aldığı bir kelimeyi temsil eden bir dizeyi alır ve noktalama olarak kabul edilen karakterleri kelimenin her yerinden kaldırır.

2. def get_pos(strSentences):

"positive_words" listesini kullanarak cümlede geçen pozitif kelimelerin sayısını bulup bu sayıyı döndürür.

3. def get_neg(strSentences):

"negative_words" listesini kullanarak cümlede geçen negatif kelimelerin sayısını bulup bu sayıyı döndürür.
 
4. def writeInDataFile(resultingDataFile):

 Bu fonksiyon proje_twitter_data.csv dosyasındaki tüm verileri temsil eden bir dize olan bir parametre alır ve bunu  result_data.csv adlı bir csv dosyasına yazar.
 
# Functions

1. def strip_punctuation(strWord):

which takes one parameter, a string which represents a word, and removes characters considered punctuation from everywhere in the word.

2. def get_pos(strSentences):

which takes one parameter, a string which represents a one or more sentences, and calculates how many words in the string are considered positive words. Use the list, positive_words to determine what words will count as positive. The function should return a positive integer - how many occurances there are of positive words in the text.

3. def get_neg(strSentences):

which takes one parameter, a string which represents a one or more sentences, and calculates how many words in the string are considered negative words. Use the list, negative_words to determine what words will count as negative. The function should return a positive integer - how many occurances there are of negative words in the text.

4. def writeInDataFile(resultingDataFile):

which takes one parameter, a string which represents all data in project_twitter_data.csv, and write a csv file called resulting_data.csv, which contains the Number of Retweets, Number of Replies, Positive Score (which is how many happy words are in the tweet), Negative Score (which is how many angry words are in the tweet), and the Net Score (how positive or negative the text is overall) for each tweet. The file have its headers in that order.


# Scatterplot


<img width="454" alt="Ekran Resmi 2021-01-15 16 27 58" src="https://user-images.githubusercontent.com/64749393/104733527-e327c780-574f-11eb-9682-abc479499e1d.png">

# resulting_data.cv Çıktısı / Output of resulting_data.cv

