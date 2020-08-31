# sagemaker-workshop

The objective of the workshop is to demonstrate SageMaker capability for machine learning developer to build, train and deploy model at scale.

## Create Notebook

- Key in the name and instance type, leave other settings as default

![image](images/create-notebook.png)

- Create a new SageMaker role. Select any S3 bucket for this demo purpose

![image](images/create-role.png)

- Fill in Git Repository

<img src="images/git-repo.png"/>

- Launch Jupyter Lab once notebook is ready

![image](images/launch-jupyterlab.png)

## Additional IAM Roles

You may need additional IAM roles depending on AWS Services that you are accessing. You can go to IAM service, select Role on the left menu and add the necessary permission to the newly created sagemaker

![image](images/attach-policy.png)
