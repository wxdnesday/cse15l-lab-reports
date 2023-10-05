# Wendy Tran - CSE 15 Lab 1 Report

---

## 1. Share an example of using the command with no arguments.
An argument is a reference being passed, such as file and directory names. Since we are not using any arguments, we will just run the command as is without a reference to anything.

* cd from working directory lecture1 leads to going into the home directory
* ls from working home directory outputs “Lab 1   lecture1”
* cat from working home directory leads to user input typing within terminal

![No Argument Commands](/images/lab1/noarg.jpg "No Argument Commands")

## 2. Share an example of using the command with a path to a directory as an argument.
Now, we will be using an argument, specifically an argument in reference to a directory, such as lecture1 and messages which are both directories that have the ability to contain files.
* “cd lecture1” from working home directory leads to going into the lecture1 directory
* “ls messages” from working directory lecture1 outputs files of messages directory
* “cat messages” from working directory lecture1 outputs “cat: messages: Is a directory”. This is because the command cat has the function of reading files and outputting its content in a readable format. So, because messages is a directory and not a file, this command outputs an error.

![Directory Argument Commands](/images/lab1/argdir.jpg "Directory Argument Commands")

## 3. Share an example of using the command with a path to a file as an argument.
Now, we will also be using an argument, however this time a file that is stored within a directory, such as the txt files in the messages directory.
* “cd vi.txt” from working directory messages leads to output “bash: cd: vi.txt: Not a directory”. This is because the command cd, or "changing directory" has the function of switching through the directories within the workspace. So, because vi.txt is not a directory, this command outputs an error.
* “ls vi.txt” from working directory messages leads to output “vi.txt”
* “cat vi.txt” from working directory messages leads to output “Chào thế giới”

![File Path Argument Commands](/images/lab1/argfile.jpg "File Path Argument Commands")

