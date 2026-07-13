Microsoft Entra ID Identity Governance Lab
Project Overview

This project demonstrates the implementation of Microsoft Entra ID Identity and Access Management (IAM) security controls in a cloud environment.

The lab focuses on protecting privileged identities, enforcing secure authentication, governing user access, and implementing Zero Trust principles using Microsoft Entra ID.

Objectives
Configure Multi-Factor Authentication (MFA)
Implement Conditional Access Policies
Configure Privileged Identity Management (PIM)
Perform Just-In-Time (JIT) role activation
Create Access Reviews for Microsoft Entra groups
Apply Identity Governance best practices
Technologies Used
Microsoft Entra ID
Microsoft Entra ID P2
Microsoft Entra ID Governance
Privileged Identity Management (PIM)
Conditional Access
Multi-Factor Authentication
Identity Governance
Microsoft 365 Admin Center
Lab Architecture



Project 1 — Multi-Factor Authentication
Objective

Increase account security by requiring users to verify their identity using multiple authentication methods.

Steps Performed
Enabled Microsoft Authenticator
Registered authentication methods
Verified successful MFA registration
Outcome

Users must provide an additional authentication factor before gaining access.



Project 2 — Conditional Access
Objective

Protect cloud resources by enforcing MFA for all users.

Configuration

Policy Name

CA001 - Require MFA for All Users

Configuration

Included all users
Excluded emergency administrator account
Targeted all cloud applications
Grant access:
Require Multi-Factor Authentication
Report-only mode for testing
Outcome

All users are required to complete MFA before accessing cloud resources.



Project 3 — Privileged Identity Management (PIM)
Objective

Reduce standing administrative privileges using Just-In-Time (JIT) access.

Configuration

Role

Security Administrator

Assignment

Eligible

Activation Requirements

MFA
Approval
Justification
Time-limited activation
Outcome

Administrative privileges are activated only when required.



Project 4 — Identity Governance
Access Reviews
Objective

Ensure only authorized users retain access to privileged groups.

Configuration

Resource

Cloud Security Team

Reviewer

Executive Management

Review Settings

Auto apply results
No change if reviewer does not respond
Justification required
Email notifications
Reminders enabled
Decision helper enabled
Sign-in inactivity recommendation
Outcome

Access reviews automate periodic certification of group membership and support least-privilege access.



Security Best Practices Implemented
Least Privilege
Zero Trust
Identity Governance
Privileged Access Management
Role-Based Access Control (RBAC)
Just-In-Time Access
Multi-Factor Authentication
Conditional Access
Skills Demonstrated
Microsoft Entra ID
Microsoft Identity Governance
Microsoft Entra ID P2
Privileged Identity Management
Conditional Access
Identity Security
Cloud Security
Azure Identity Management
Zero Trust
RBAC
Access Reviews
Future Improvements
Microsoft Sentinel integration
Identity Protection
Risk-Based Conditional Access
User Lifecycle Workflows
Entitlement Management
Access Packages
Automated Remediation
Author

Oni Victor Kehinde

SOC Analyst | Cloud Security | Microsoft Entra ID | Microsoft Sentinel | Identity & Access Management (IAM)

