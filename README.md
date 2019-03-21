### Deploy from jenkins to multiple servers using ansible

blue green deployment will do 

1. Stop tomcat gresfully 

2. Remove devops.html file to get out of the loadbalancer

3. Deploy the package

4. Make sure that the URL after deployment is working 

5. Create devops.html file to get back to the loadbalancer
