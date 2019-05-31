# MANDATORY PREREQUISITES

Check list for this lab

[Also you can have detail instruction for the prerequisites](https://github.com/xlegend1024/azlab-ai-ops/blob/master/MandatoryLabPreReqs.pdf)

## Azure DevOps

Do you have access to [Azure DevOps](https://devops.azure.com)?

##

Do you have Azure Subscription?

Do you have a Resource Group with Owner role?

Do you have a Service Principal as contributor in the Resource Group that you're assigned as Owner?

Do you know the Service Pricipal Application ID?

Do you know the Service Pricipal Secret?

Do you know the Service Pricipal Tenant ID?

> About the Service Principal
>
> The Service principal and credentials will be used for authentication within the AML pipelines.  Because a Service principal is created outside of the subscription ( it is created in Azure Active Directory), in order to use it for AML pipelines, the Service principal needs to be assigned Role Based Access Control (RBAC) permissions within the azure subscription. An administrator for the azure subscription will need to add the Service principal to the azure subscription with the appropriate permissions
>
