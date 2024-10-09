# Login Test Automation Framework

This is a basic test automation framework designed to automate the login functionality of a website using Selenium, TestNG, and the Page Object Model pattern.

## Requirements

- Java 8+
- Maven
- Google Chrome Browser
- ChromeDriver

## Dependencies

All required dependencies are managed in the `pom.xml` file.

### Key Libraries
- **Selenium** for WebDriver
- **TestNG** for testing

  
## Setup Instructions

1. Import the project:
    ```
    git clone https://github.com/ziniann/sauceDemoSimpleWeb.git
    ```
    ```
    cd sauceDemoSimpleWeb
    ```
2. Build the project using Maven:
    ```
    mvn clean install
    ```
3. Run the test suite:
    ```
    mvn test
    ```
## Reports

After running the tests, the test results will be available in the `testng-results.xml`.

## Test Cases

1. **verifySuccessfulLogin**: Verifies successful login with valid credentials.
2. **verifyLoginFailure**: Verifies that login fails with incorrect credentials.
