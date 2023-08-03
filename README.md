# k8sdvwa
this is for k8s dvwa(DAMN VULNERABLE WEB APPLICATION) environment.
## notice
1. Do not use these tools in public or any environment that may cause problems. If you are not sure, do not use them.
2. This environment separates the DVWA web application, configuration, and database into separate pods, and uses Kubernetes services to connect them.
## how to
1. kubectl create cm config.inc.php --from-file=config.inc.php
2. kubectl create -f mydb4dvwa-init.yaml
3. kubectl create -f dvwa.yaml
and Enjoy it.
