# What Is Amazon Elastic Container Registry?<a name="what-is-ecr"></a>

Amazon Elastic Container Registry \(Amazon ECR\) is a managed AWS Docker registry service that is secure, scalable, and reliable\. Amazon ECR supports private Docker repositories with resource\-based permissions using AWS IAM so that specific users or Amazon EC2 instances can access repositories and images\. Developers can use the Docker CLI to push, pull, and manage images\.

## Components of Amazon ECR<a name="ecr-components"></a>

Amazon ECR contains the following components:

Registry  
An Amazon ECR registry is provided to each AWS account; you can create image repositories in your registry and store images in them\. For more information, see [Amazon ECR Registries](Registries.md)\.

Authorization token  
Your Docker client must authenticate to Amazon ECR registries as an AWS user before it can push and pull images\. For more information, see [Registry Authentication](Registries.md#registry_auth)\.

Repository  
An Amazon ECR image repository contains your Docker or Open Container Initiative \(OCI\) images\. For more information, see [Amazon ECR Repositories](Repositories.md)\.

Repository policy  
You can control access to your repositories and the images within them with repository policies\. For more information, see [Amazon ECR Repository Policies](repository-policies.md)\.

Image  
You can push and pull container images to your repositories\. You can use these images locally on your development system, or you can use them in Amazon ECS task definitions\. For more information, see [Using Amazon ECR Images with Amazon ECS](ECR_on_ECS.md)\.

## How to Get Started with Amazon ECR<a name="ecr-get-started"></a>

To use Amazon ECR, you must be set up to install the AWS Command Line Interface and Docker\. For more information, see [Setting Up with Amazon ECR](get-set-up-for-amazon-ecr.md) and [Getting Started with Amazon ECR using the AWS CLI](getting-started-cli.md)\.