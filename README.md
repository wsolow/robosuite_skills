# Robosuite Skills 

A repository based on the paper and code found here: https://github.com/UT-Austin-RPL/maple. This has been updated to Robosuite v1.5, Python 3.11, and Mujoco 3.4.0

## Installation 

1. Use a conda virtual environment: 
    ```conda create -n robosuite python=3.11```

    ```conda activate robosuite```

2. Navigate to robosuite and install requirements

    a. Install robosuite
    ```cd robosuite```
    ```pip install -r requirements.txt```
    ```pip install -r requirements-extra.txt```
    ```cd ..```
    
    b. Install maple
    ```pip install -e maple```

    c. Install other requirements
    ```pip install python-dateutil torch torchvision gtimer```

### Usage
See https://github.com/UT-Austin-RPL/maple for instructions on how to run experiments

See https://robosuite.ai/docs/overview.html for instructions on robosuite




