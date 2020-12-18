## 🔰 Ansible PlayBook that does the following operations in the managed nodes 🔹

### Docker 

- Configure Docker

- Start and enable Docker services

- Pull the httpd server image from the Docker Hub

- Run the docker container and expose it to the public

- Copy the html code in /var/www/html directory and start the web server


### Web-server 

- Mount the redhat-dvd which contains 6000+ softwares

- Configuration of yum

- Installation of httpd software

- Change the document root to /var/www/lw

- Change the port number to 8080

- Copy the web-pages

- Restart the service

- Will allow firewall traffic on port 8080

NOTE: By default, apache web-server works on tcp port and port number 80 and the document root is /var/www/html.

### How to send mail using ansible?

- For sending mail, first create a vault(secret.yml) which contains your mail id and password.

- Replace the mail id xyz@gmail.com with the mail id of recipient.

- Run the playbook mail.yml using the command "ansible-playbook mail.yml".

## How to get started?

- Clone the repository.

- Copy the code in the ansible controller node.

- Cd to the location of the code file.

- Run the command "ansible-playbook (filename)".
