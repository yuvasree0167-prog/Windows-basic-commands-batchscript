# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"
## OUTPUT
<img width="530" height="195" alt="Screenshot 2026-05-21 090308" src="https://github.com/user-attachments/assets/a763717f-e479-46cc-8e5e-6884be7d18b1" />



Remove the directory "my-folder"
## OUTPUT
<img width="632" height="123" alt="Screenshot 2026-05-21 090451" src="https://github.com/user-attachments/assets/639ddf14-790e-4c86-829e-e8b21166ee7f" />



Create the file Rose.txt
## OUTPUT
<img width="611" height="140" alt="Screenshot 2026-05-21 091056" src="https://github.com/user-attachments/assets/beb5ea13-afb9-40ae-a8a5-ac663beb1788" />
<img width="712" height="231" alt="Screenshot 2026-05-21 091106" src="https://github.com/user-attachments/assets/2eec0bff-a804-44da-bd9b-1cd8378f8d80" />


Create the file hello.txt using echo and redirection
## OUTPUT
<img width="686" height="115" alt="Screenshot 2026-05-21 091145" src="https://github.com/user-attachments/assets/f2d97ea6-cb88-4417-a98f-82adbf61234e" />


Copy the file hello.txt into the file hello1.txt
## OUTPUT
<img width="588" height="140" alt="Screenshot 2026-05-21 091225" src="https://github.com/user-attachments/assets/3fcfe7cf-25d7-4b75-8e8a-e89bffe167fd" />

Remove the file hello1.txt


List out the file hello1.txt in the current directory
## OUTPUT
<img width="493" height="232" alt="Screenshot 2026-05-21 091300" src="https://github.com/user-attachments/assets/afa3e69b-8c23-4341-a8fa-b9683fa06b26" />

List out all the associated file extensions 
## OUTPUT
<img width="573" height="278" alt="Screenshot 2026-05-21 091331" src="https://github.com/user-attachments/assets/9bd126d1-a119-47bc-b184-6e306fcc9fc5" />


Compare the file hello.txt and rose.txt
## OUTPUT
<img width="530" height="176" alt="Screenshot 2026-05-21 091519" src="https://github.com/user-attachments/assets/1f7b0fef-7e0d-438a-9e4c-ce6aa5145520" />


## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="432" height="84" alt="Screenshot 2026-05-21 092110" src="https://github.com/user-attachments/assets/717cf14a-4089-4c26-9a0e-74993f3643c2" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="532" height="190" alt="Screenshot 2026-05-21 092256" src="https://github.com/user-attachments/assets/cfc394b8-d8c7-4b40-86ea-dc258f2782aa" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="420" height="165" alt="Screenshot 2026-05-21 092455" src="https://github.com/user-attachments/assets/1c34725d-0fc0-4f28-b9cf-7ca8ce32634b" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="635" height="176" alt="Screenshot 2026-05-21 092541" src="https://github.com/user-attachments/assets/aad9f1a9-11e7-476c-ae02-204932666f73" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="545" height="346" alt="Screenshot 2026-05-21 092616" src="https://github.com/user-attachments/assets/dc961bdb-c47d-44e4-89a6-f9a6f5817c1f" />



# RESULT:
The commands/batch files are executed successfully.

