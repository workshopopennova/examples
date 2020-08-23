yum install ansible-2.9.11-1.el8ae.noarch.rpm ansible-freeipa-0.1.8-3.el8.noarch.rpm sshpass-1.06-3.el8ae.x86_64.rpm

ansible-playbook idm_add_user.yml -e 'usuario=andy.reyes nombre=Andy apellido=Reyes clave=Passw0rd$'
