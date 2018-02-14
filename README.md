# dockerfile
# alpine dockerfile


2  5%
Monitor the logs Pod foo and:
Extract log lines corresponding to error fine-not-found
Write them to /opt/KULM00201/foo

3 3%
List all PVs storted by capacity, saving the full kubectl output to /opt/KUCC00102/persistend_volumes. Use kubectl sown functionality for sorting the output, and do not manipulate it any further.

4 3%
Ensure s single instance of Pod nginx is running on each node of the Kubernetes cluster where nginx also reqressents the image name which has to bu used. Do not overide any taints curently in place.
Use DaemonSets to complete this task and use ds-kusc00201 as DaenonSet name.



6 4%
Create a pod named kucc1 with a single container for each of the following images running inside (there may be between 1 and 4 images specifed): nginx+redis

7  2%
Schedule a Pod as follows
  name: nginx-kusc00101
  Image: nginx
  Node sclector: disk=ssd

8   4% 版本回滚
Creata a aeployment as follows:
name: nginx-app
Using container: nginx with version 1.11.10-alpine
The deployment should contain 3 replicas

Next, deploy the app with new version 1.11.13-alpine, by perfoming a rolling update, and record that update.
Finally, rollback that update to the previous 1.11.10-alpine

9 3%
Create abd cibfigure the service front-end-server so it`s accessible through NodePort and routes to the existing pod baned front-end

10 3%
Create a Pod as follows:
Name: jinkins
Using image: jenkins
In a new Kubernetes namespace named: my-application.

11 3%

Create a deployment spec file that will:
Launch: 7 replicas of the redis image with the label: app_env_stage=test
Deployment naem: kual00201
Save a copy of this spec file to /opt/KUAL00201/spec_deploy.yaml(of .json)
When you are done, clean up(delete) any new k8s API objects that you produced during this task.

12 3%
Create a file: /opt/KUCC00302/kucc00302.txt that list all pods that implement Service bar in Namespace development 
The format of the file should be one pod name per line 

13 

14 4% 创建一个pod yaml
Create a pod as follows:
-Name: non-persisten-redis
Container image: redis
Named-Volume with name: app-cache
Mount path: /data/redis
It should launch in the qa namespace and the volume MUST NOT be persistent

15 1%

Scale the deployment presentation to 6 pods 

##kubectl scale --replicas=6 deployment/presentaion

16 2%
Check to see how many nodes are ready (not including nodes tainted NoSchedule) and write the number to /opt/KUCC00104.txt

##

17 2%
From the Pod label name=cpu-user, find pods running high CPU workloads write the name of the Pod consuming most CPU to the file /opt/KUTR00102/KUTR00102.txt(which already exists).

18 7%

Create a deploymen as follows:
Name:nginx-random
Exposed via service: nginx-random
Ensure that the service & pod are accessible via the  reqective


25 4%
Given a partially-functioning Kubernetes cluster,identify symptoms of failure on the cluster.
