# JunctionX Seoul 2020

## SmartMonitor

Detect damaged building by natural disasters and get a brief information about it.

### Contributors
- **Nikita Rusetskii (me)** <a target="_blank" href="https://www.linkedin.com/in/xtenzq/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5.svg?&style=flat-badge&logo=linkedin&logoColor=white" /></a> <a target="_blank" href="https://github.com/xtenzQ" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717.svg?&style=flat-badge&logo=github&logoColor=white" /></a>
- **Konstantin Shusterzon** <a target="_blank" href="https://www.linkedin.com/in/konstantin-shusterzon-a9aa02181/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5.svg?&style=flat-badge&logo=linkedin&logoColor=white" /></a> <a target="_blank" href="https://github.com/Exterminant" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717.svg?&style=flat-badge&logo=github&logoColor=white" /></a>
- **Kirill Zenin** <a target="_blank" href="https://www.linkedin.com/in/bloodghastzk/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5.svg?&style=flat-badge&logo=linkedin&logoColor=white" /></a> <a target="_blank" href="https://github.com/KirillZenin" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/GitHub-181717.svg?&style=flat-badge&logo=github&logoColor=white" /></a>

### Technologies used
For development of the web app we used following technologies:
- ASP.NET Core;
- [Bulma](https://bulma.io);
- [NewsAPI](https://newsapi.org);

Machine learning side was developed with **PyTorch**. We used Res-Net50 pretrained on COCO dataset.

### How it works
1. Pick up a natural disaster;
2. Check news and photos with detected by ResNet damaged houses

### Presentation
Check on [Google Docs](https://docs.google.com/presentation/d/e/2PACX-1vQGgs65mox96CRPLiuKG7pkToq_3VL4xF8cz6vKprEPQI5A4dg9TZyJkIb6WLY3hIrAt9Pazc-4pzoj/pub)

### Future plans
Due to the lack of experience we haven't managed to successfully integrate it with Azure and deploy it but we're looking forward to improve our project!
Our future plans are:
- [ ] Azure integration;
- [ ] Adding data storage;
- [ ] Better natural disaster news aggregation;
- [ ] Retraining neural network to be able to detect other objects and show more detailed information about damage;
- [ ] Azure/DigiatOcean Deployment
