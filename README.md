# ansible
#instalar
sudo apt-get update
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
ansible-playbook 

#estrutura de arquivos
/app/hosts  
/app/playbook.yml  
/app/group_vars/all  


#executar
ansible-playbook -i hosts playbook.yml --ask-pass --ask-become-pass

https://www.digitalocean.com/community/tutorials/how-to-deploy-a-basic-php-application-using-ansible-on-ubuntu-14-04


