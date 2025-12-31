# ☁️ Cloud-Native Container Deployment (AWS & Docker)

A professional DevOps starter project demonstrating the manual "Lift and Shift" of a Python microservice into a cloud environment.

## 🚀 Project Overview
This project showcases the end-to-end process of containerizing a Python Flask application and deploying it to a production-grade AWS EC2 instance. It serves as a foundation for understanding cloud infrastructure and container orchestration.

## 🛠 Tech Stack
* **Language:** Python 3.9 (Flask Framework)
* **Containerization:** Docker
* **Registry:** Docker Hub
* **Cloud Provider:** Amazon Web Services (AWS)
* **Compute:** EC2 (Ubuntu 22.04 LTS)
* **OS/Shell:** Linux (Kubuntu/Bash)

## 🏗 Architecture
1. **Local Development:** Built and tested a Flask microservice inside a Kubuntu VM.
2. **Containerization:** Created a custom Dockerfile to package the app and its dependencies.
3. **Distribution:** Tagged and pushed the image to a public Docker Hub repository.
4. **Cloud Provisioning:** Launched an AWS EC2 instance with custom Security Groups (Ports 22 & 80).
5. **Production Deployment:** Pulled the image from Docker Hub onto the AWS server and launched the container.

## 📸 Proof of Concept
I successfully verified the deployment by accessing the AWS Public IP.
> **Status:** Running inside container: `c9bfb43247c0`

## 🏁 Key Learnings
* **Docker Fundamentals:** Writing Dockerfiles, managing images, and port mapping.
* **AWS Networking:** Configuring Security Groups (firewalls) to allow web traffic.
* **Linux Administration:** Navigating remote servers via SSH and managing the Docker Engine CLI.
* **Troubleshooting:** Resolving virtualization conflicts and managing Git authentication tokens.
