# Module 5 Challenge: Password Generator

## Overview

This week’s challenge requires you to create an application that an employee can use to generate a random password based on criteria they’ve selected by modifying starter code. This app will run in the browser, and will feature dynamically updated HTML and CSS powered by JavaScript code that you write. It will have a clean and polished user interface that is responsive, ensuring that it adapts to multiple screen sizes.

The password can include special characters. If you’re unfamiliar with these, see this [list of Password Special Characters from the OWASP Foundation](https://www.owasp.org/index.php/Password_special_characters).

## Instructions

The following image shows the web application's appearance and functionality:

![password generator demo](./assets/05-javascript-challenge-demo.png)


* Generate a password when the button is clicked
  * Present a series of prompts for password criteria
    * Length of password
      * At least 8 characters but no more than 128.
    * Character types
      * Lowercase
      * Uppercase
      * Numeric
      * Special characters ($@%&*, etc)
  * Code should validate for each input and at least one character type should be selected
  * Once prompts are answered then the password should be generated and displayed in an alert or written to the page

## Grading Requirements

This challenge is graded based on the following criteria: 

### Technical Acceptance Criteria: 40%

* Satisfies all of the above acceptance criteria plus the following:

  * The challenge should not produce any errors in the console when you inspect it using Chrome DevTools.

### Deployment: 32%

* Application deployed at live URL.

* Application loads with no errors.

* Application GitHub URL submitted.

* GitHub repository that contains application code.

### Application Quality: 15%

* Application user experience is intuitive and easy to navigate.

* Application user interface style is clean and polished.

* Application resembles the mock-up functionality provided in the challenge instructions.

### Repository Quality: 13%

* Repository has a unique name.

* Repository follows best practices for file structure and naming conventions.

* Repository follows best practices for class/id naming conventions, indentation, quality comments, etc.

* Repository contains multiple descriptive commit messages.

* Repository contains quality README file with description, screenshot, and link to deployed application.


## Review

You are required to submit the following for review:

* The URL of the deployed application.

* The URL of the GitHub repository. Give the repository a unique name and include a README describing the project.

---

© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.
..............................................................................
# steps that has been taken
This README provides a quick overview of how to use the password generator, its features, and the structure of the code. It also encourages users to feel free to use and modify the generator for their own projects.
# Password Generator
This simple password generator allows users to specify password criteria, including length and character types, and generates a secure password accordingly. The generator ensures that at least one character from each selected type is included in the final password.

## Usage

1. Open the `index.html` file in a web browser.
2. Click the "Generate Password" button.
3. Follow the prompts to set password criteria:
   - Enter the length of the password (between 8 and 128 characters).
   - Choose whether to include lowercase, uppercase, numeric, and special characters.
4. After answering prompts, the generated password will be displayed on the page.

## Features
- Password length validation: Ensures the entered length is within the specified range.
- Character type validation: Requires at least one character type to be selected.
- Secure password generation: Generates a password meeting user-specified criteria.

## Code Structure
- `getPasswordOptions`: Function to prompt the user for password criteria.
- `getRandom`: Function to get a random element from an array.
- `generatePassword`: Function to generate a password based on user choices.
- `writePassword`: Function to display the generated password on the page.
- Event listener on the "Generate Password" button triggers the password generation.

Feel free to use, modify, and integrate this password generator into your projects!

