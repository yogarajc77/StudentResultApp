Student Result App :
A simple Java console-based application to manage and display student results.
This project allows users to enter student details, calculate total marks, percentage, and grade, and display the final result in a clean formatted output.

Features:
Enter student information (Name, Roll Number)
Input marks for multiple subjects
Calculate:
   Total Marks
   Percentage
   Grade
Display detailed result card
Error handling for invalid input
Clean and beginner-friendly Java code

Project Structure:
StudentResultApp/
│
├── src/
|     ├── Main.java
├── WebContent
     └── index.html

Technologies Used:
Java SE 8+
Collections / OOP Concepts
Scanner for input

How to Run:
Method 1: Using Command Prompt / Terminal
cd StudentResultApp
javac Main.java
java Main

Method 2: Using an IDE
You can import the project into:
IntelliJ IDEA
Eclipse
VS Code with Java Extensions
Simply run the Main class.

Sample Output:
Enter Student Name: yogaraj
Enter Roll Number: 101
Enter Number of Subjects: 3

Enter marks for Subject 1: 78
Enter marks for Subject 2: 85
Enter marks for Subject 3: 90

------------ RESULT ------------
Name: yogaraj
Roll No: 101
Total Marks: 253 / 300
Percentage: 84.33%
Grade: A
--------------------------------

Grading Criteria:
Percentage	Grade
>= 90       	A+
80–89	        A
70–79	        B
60–69	        C
< 60	        D


Code Overview:
Student.java:
Holds student info (name, roll number, marks)

ResultCalculator.java:
Computes total, percentage, grade

Main.java:
User interaction
Takes input and prints result

Requirements:
JDK 8 or above
Basic terminal/IDE setup

Contributing:
Pull requests are welcome.
For major changes, please open an issue first to discuss what you want to change.

License:
This project is open-source and free to use.
