# Terrafom-Gov-Cloud-EKS-for-Wiz-Demos
A quick setup to deploy EKS in existing VPC in GOV cloud

``
git clone # click the green buttun to copy your GH link <insert link after git clone> cd (name of output of the "ls" command
``  

``
terraform init
``  

``
terraform plan
``  

``
terraform apply
``  

#You can install this to make it faster For macOS

``
brew install aws-iam-authenticator
``  

``
aws eks --region us-gov-east-1 update-kubeconfig --name my-eks-cluster
``  


## Follow for more testing and deployment scenerios for EKS

``
kubectl apply -f # The following files in this repo
``  

