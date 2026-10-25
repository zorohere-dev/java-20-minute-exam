# Java Fundamentals — 20-Minute Exam

**Time limit:** 20 minutes  
**Total marks:** 20  
**Instructions:** Complete the questions in Java. Do not include solutions in the README. Save your code in the appropriate `.java` files and submit your repository link to your instructor.

## Student details
- **Name:**
- **Student ID:**
- **Date:**

## Rules
1. Attempt all questions.
2. Write readable Java code and use meaningful variable names.
3. For coding questions, include a `main()` method where requested.
4. Do not copy code from classmates or online solutions.
5. Commit and push your completed files to your own GitHub repository before submitting.

## Section 1 — Fundamentals (3 marks; 3 minutes)

### Q1. JDK, JRE and JVM (1 mark)
Explain the difference between the JDK, JRE and JVM, and briefly describe how they relate to running a Java program.

### Q2. Primitive data types (1 mark)
Identify the data type used by each variable below and explain what kind of value it stores.
```java
int age = 25;
double salary = 45000.50;
char grade = 'A';
boolean isActive = true;
```

### Q3. Methods (1 mark)
What is a Java method? Explain the difference between defining a method and calling a method.

## Section 2 — Predict the output (3 marks; 3 minutes)

### Q4. Expressions (1 mark)
Without running the code, write the exact output.
```java
int a = 10;
int b = 3;

System.out.println(a + b);
System.out.println(a / b);
System.out.println(a % b);
```

### Q5. Conditionals (1 mark)
What does this program print? Explain briefly.
```java
int x = 5;

if (x > 10) {
    System.out.println("Greater");
} else {
    System.out.println("Smaller");
}
```

### Q6. For loop (1 mark)
How many times does `Hello World` print?
```java
for (int i = 1; i <= 4; i++) {
    System.out.println("Hello World");
}
```

## Section 3 — Coding challenges (9 marks; 9 minutes)

### Q7. Multiplication table (3 marks)
Write a Java program that uses a `for` loop to print the multiplication table of 7, from `7 x 1` through `7 x 10`. Save it in `Q7MultiplicationTable.java`.

### Q8. Conditional statements (3 marks)
Write a Java program that checks whether an integer is positive, negative or zero using `if`, `else if` and `else`. Save it in `Q8NumberCheck.java`.

### Q9. Methods (3 marks)
Create a method named `multiply` that accepts two integers and returns their product. Call it from `main()` and print the result. For example, inputs `6` and `4` should produce `24`. Save it in `Q9MultiplyMethod.java`.

## Section 4 — Classes and objects (5 marks; 5 minutes)

### Q10. Create a `MotorBike` class (5 marks)
Create a class named `MotorBike` with:
- An integer instance variable named `speed`.
- A method named `displaySpeed()` that prints the speed.
- A `main()` method that creates a `MotorBike` object, assigns `speed = 60`, and calls `displaySpeed()`.

Also explain briefly what a class and an object are, and why an object is created. Save your code in `Q10MotorBike.java`.

## Submission checklist
- [ ] Answered all questions in `README.md` or in a separate `ANSWERS.md` file.
- [ ] Added code files for Q7–Q10.
- [ ] Ran the programs in Eclipse or another Java IDE.
- [ ] Committed and pushed the completed work to GitHub.
- [ ] Shared the repository URL with the instructor.
