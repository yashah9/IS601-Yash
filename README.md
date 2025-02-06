# **Assignment Completion Report**  

I have successfully completed the required setup and testing for this assignment. Below are the steps I followed:  

## **1. Python Installation**  
- Installed Python using **Brew** (Mac) .  
- Verified installation using:  
  ```sh
  pip3 --version
  ```

## **2. Virtual Environment Setup**  
- Installed `virtualenv` globally using:  
  ```sh
  pip3 install virtualenv
  ```
- Created a new project directory and set up a virtual environment:  
  ```sh
  mkdir myproject
  cd myproject
  python3 -m venv venv
  source ./venv/bin/activate
  ```
  
## **3. Cloning and Testing with Git**  
- Cloned the provided repository and installed dependencies:  
  ```sh
  git clone git@github.com:kaw393939/git_python_testing_setup_homework.git
  cd git_python_testing_setup_homework
  source venv/bin/activate
  pip3 install -r requirements.txt
  ```
- Ran tests to verify setup:  
  ```sh
  pytest --pylint --cov
  ```

## **4. Project Initialization**  
- Created `calculator/` and `tests/` directories with `__init__.py` files.  
- Added `.gitignore`, `.pylintrc`, and `pytest.ini` with required configurations.  
- Implemented the necessary code in `calculator/__init__.py` and `tests/test_calculator.py`.

## **5. Running Tests**  
- Ran different test configurations to validate the project:  
  ```sh
  pytest                # Runs tests  
  pytest --pylint       # Runs tests with pylint  
  pytest --pylint --cov # Runs tests, pylint, and coverage  
  ```

## **6. Freezing Dependencies**  
- Created `requirements.txt` to track dependencies:  
  ```sh
  pip3 freeze > requirements.txt
  ```

## **7. Pushing to GitHub**  
- Created a new branch `hw2` and pushed my changes:  
  ```sh
  git checkout -b hw2
  git add .
  git commit -m "Completed HW2"
  git push -u origin hw2
  ```

## **8. Submission**  
- Verified my repository and submitted the GitHub link to Canvas.

Everything has been set up and tested successfully. 🚀✅  
