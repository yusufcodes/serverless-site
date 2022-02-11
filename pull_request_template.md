# PR Checklist
Before opening up your PR for review, double check everything below has been completed!

### Testing
- [ ] Tests have been written for all new features (unit, integration, E2E), and all tests (new and existing) are passing

### Source Control
- [ ] Commits have been renamed, squashed & dropped if necessary

### Monitoring, Logging & Alerting
- [ ] New alarms added and where necessary, old alarms have been removed
- [ ] External calls have duration metrics using kebab case _(e.g. kebab-case)_
- [ ] Dashboards have been created/updated in DEV, UAT & PROD   
  - [ ] [Loyalty Documentation](https://github.com/Moonpig/moonpig-docs-loyalty/blob/master/Monitoring%2C%20Alerting%20and%20Logging.md) has been updated with links to these dashboards

### Documentation
- [ ] Updates to the README have been made where needed (architecture, running locally, etc.)
- [ ] JIRA ticket has been updated to reflect any changes to the ticket requirements

### UI Changes (if applicable) 
- [ ] Image / video shared with PM / Designer
