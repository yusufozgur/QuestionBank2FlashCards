# QuestionBank2FlashCards
Converts question and answer sheets with multiple chapters into a nice format that flashcard apps can import.

Often times students encounder question banks with multiple chapters and many questions with their answers, and they need to convert those question banks into flashcards by hand.

This script takes an example question bank such as the following.

```
Page 1
Chapter 1
1. Question 1
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5
2. Question 2 with 
multiple lines
of
text
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5
Page 2
3. Question 3
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5
Page 3
Answer Key
1.
E
2.C
3.
A
Chapter 2
4. Question 4
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5

Answer Key
1.
B
```

Then the script converts it to a text file such as the following for each chapter

```
1. Question 1
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5

E) Answer 5


2. Question 2 with 
multiple lines
of
text
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5

C) Answer 3


3. Question 3
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5

A) Answer 1


4. Question 4
A) Answer 1
B) Answer 2
C) Answer 3
D) Answer 4
E) Answer 5

B) Answer 2
```


