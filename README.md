# awesome-agentic-commerce

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of resources on **Agentic Commerce (A-Commerce)**, covering agentic e-commerce, multi-agent market and commerce systems, conversational commerce, autonomous negotiation and trading, recommendation/search agents, pricing agents, supply chain and logistics agents, and payment agents.

This repository complements the survey:

> **Agentic Commerce: A Survey of How AI Agents Are Reshaping Commerce**  
> [TechRxiv Preprint](https://www.techrxiv.org/doi/full/10.36227/techrxiv.176972193.39211542/v1)

```bibtex
@article{zhang2026agentic-commerce,
  title={Agentic Commerce: A Survey of How AI Agents Are Reshaping Commerce},
  author={Zhang, Yifei and Pan, Bo and Zhu, Mengdan and Pei, Jian and Zhao, Liang},
  journal={TechRxiv},
  year={2026},
  doi={10.36227/techrxiv.176972193.39211542/v1},
  url={https://www.techrxiv.org/doi/full/10.36227/techrxiv.176972193.39211542/v1}
}
```

![From Traditional Commerce to E-Commerce to Agentic Commerce](assets/a-commerce.png)

## Industry Reports & Whitepapers

* [Boston Consulting Group 2025] Agentic Commerce Is Redefining Retail — Here's How to Respond. [link](https://www.bcg.com/publications/2025/agentic-commerce-redefining-retail-how-to-respond)
* [McKinsey & Company 2025] The Agentic Commerce Opportunity: How AI Agents Are Ushering in a New Era for Consumers and Merchants. [link](https://www.mckinsey.com/capabilities/quantumblack/our-insights/the-agentic-commerce-opportunity-how-ai-agents-are-ushering-in-a-new-era-for-consumers-and-merchants)
* [Mastercard 2025] What is agentic commerce? Your guide to AI-assisted retail. [link](https://www.mastercard.com/global/en/news-and-trends/stories/2025/agentic-commerce-explainer.html)
* [Visa 2025] What Is Agentic Commerce? [link](https://corporate.visa.com/en/sites/visa-perspectives/innovation/what-is-agentic-commerce.html)
* [Google Cloud 2025] Agentic commerce is here: How retailers can prepare for the new shopping era [link](https://cloud.google.com/transform/agentic-commerce-retailers-can-prepare-for-the-new-shopping-era-ai)
* [Shopify 2025] AI Agents: Harnessing Agentic AI for Ecommerce Businesses [link](https://www.shopify.com/blog/ai-agents)
---

## Part I: Commerce Pipeline (Survey Taxonomy)

*Organization: **Stage** → **Agent Role** (as defined in the survey).*  
*Lifecycle stages (§2): Awareness → Discovery → Engagement → Decision → Transaction → Fulfillment → Service.*

![Agentic Commerce pipeline and agent roles across lifecycle stages](assets/pipeline.png)

### Awareness

> **Stage focus:** pre-intent exposure and demand formation (who gets seen, when, and under what constraints)

#### Merchant-Agent

* [arXiv] CAL-RAG: Retrieval-Augmented Multi-Agent Generation for Content-Aware Layout Design. [link](https://arxiv.org/pdf/2506.21934)
* [EMNLP Industry 2024] IPL: Leveraging Multimodal Large Language Models for Intelligent Product Listing. [link](https://aclanthology.org/2024.emnlp-industry.52.pdf)
* [WWW Companion 2025] RTBAgent: A LLM-based Agent System for Real-Time Bidding. [link](https://arxiv.org/pdf/2502.00792)
* [arXiv] MAAMS: Agentic Multimodal AI for Hyperpersonalized B2B and B2C Advertising in Competitive Markets (AI-Driven Competitive Advertising Framework). [link](https://arxiv.org/pdf/2504.00338)
  
#### Platform-Agent

* [arXiv] PersonaX: A recommendation agent oriented user modeling framework for long behavior sequence. [link](https://arxiv.org/pdf/2503.02398)
* [KDD 2023] NEON: Living Needs Prediction System in Meituan. [link](https://arxiv.org/pdf/2307.16644)
* [arXiv] Rec-R1: Bridging generative large language models and user-centric recommendation systems via reinforcement learning. [link](https://arxiv.org/pdf/2503.24289)

#### Consumer-Agent

*Largely unexplored today; a promising future direction highlighted by the survey (§3.1).*
---

### Discovery

> **Stage focus:** intent-grounded exploration via search and recommendation (finding plausible candidates, not committing)

#### Consumer-Agent

* [arXiv] ShoppingBench: A Real-World Intent-Grounded Shopping Benchmark for LLM-based Agents. [link](https://arxiv.org/pdf/2508.04266)
* [NeurIPS 2022] WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents. [link](https://arxiv.org/pdf/2207.01206)
* [arXiv] iAgent: LLM Agent as a Shield between User and Recommender Systems. [link](https://arxiv.org/pdf/2502.14662)
* [REALM 2025] PAARS: Persona aligned agentic retail shoppers. [link](https://arxiv.org/pdf/2503.24228)

#### Platform-Agent

* [SIGIR 2024] MACRec: A Multi-Agent Collaboration Framework for Recommendation. [link](https://dl.acm.org/doi/abs/10.1145/3626772.3657669)
* [arXiv] ARAG: Agentic Retrieval Augmented Generation for Personalized Recommendation. [link](https://arxiv.org/pdf/2506.21931)
* [arXiv] RecMind: Large Language Model Powered Agent For Recommendation. [link](https://arxiv.org/pdf/2308.14296)
* [arXiv] CARTS: Collaborative Agents for Recommendation Textual Summarization. [link](https://arxiv.org/pdf/2506.17765)
* [SIGIR 2024] Let Me Do It For You: Towards LLM Empowered Recommendation via Tool Learning. [link](https://dl.acm.org/doi/abs/10.1145/3626772.3657828)
* [arXiv] AgentCF: Collaborative Learning with Autonomous Language Agents for Recommender Systems. [link](https://arxiv.org/pdf/2310.09233)
* [WWW 2025] LREF: A Novel LLM-based Relevance Framework for E-commerce Search. [link](https://dl.acm.org/doi/pdf/10.1145/3701716.3715246)
* [ACL Industry 2025] User Feedback Alignment for LLM-powered Exploration in Large-scale Recommendation Systems. [link](https://aclanthology.org/2025.acl-industry.70.pdf)
* [arXiv] LORE: A Large Generative Model for Search Relevance. [link](https://arxiv.org/pdf/2512.03025)
* [WSDM 2025] Enhancing E-Commerce Query Rewriting: A Large Language Model Approach with Domain-Specific Pre-Training and Reinforcement Learning. [link](https://dl.acm.org/doi/epdf/10.1145/3627673.3680109)
* [arXiv] LocalSearchBench: Benchmarking Agentic Search in Real-World Local Life Services. [link](https://www.arxiv.org/pdf/2512.07436)
* [arXiv] LocalGPT: Benchmarking and Advancing Large Language Models for Local Life Services in Meituan. [link](https://arxiv.org/pdf/2506.02720)
* [arXiv] Enterprise Deep Research: Steerable MultiAgent Deep Research for Enterprise Analytics. [link](https://arxiv.org/pdf/2510.17797)
* [arXiv] Beyond Retrieval-Ranking: A Multi-Agent Cognitive Decision Framework for E-Commerce Search. [link](https://arxiv.org/pdf/2510.20567)
* [SIGIR 2024] On Generative Agents in Recommendation. [link](https://dl.acm.org/doi/pdf/10.1145/3626772.3657844)
---

### Engagement

#### Consumer-Agent

* [arXiv] ChatShop: Interactive information seeking with language agents. [link](https://arxiv.org/pdf/2404.09911)
* [arXiv] The Automated but Risky Game (A2A-NT): Modeling Agent-to-Agent Negotiations and Transactions in Consumer Markets. [link](https://arxiv.org/pdf/2506.00073v3)
* [arXiv] Advancing AI Negotiations: New Theory and Evidence from a Large-Scale Autonomous Negotiation Competition. [link](https://arxiv.org/pdf/2503.06416)

#### Merchant-Agent

* [EMNLP 2025] ASTRA: A Negotiation Agent with Adaptive and Strategic Reasoning via Tool-integrated Action for Dynamic Offer Optimization. [link](https://aclanthology.org/2025.emnlp-main.821.pdf)
* [WWW Companion 2025] FishBargain: An LLM-Empowered Bargaining Agent for Online Fleamarket Platform Sellers. [link](https://arxiv.org/pdf/2502.10406)
* [arXiv] SalesRLAgent: A Reinforcement Learning Approach for Real-Time Sales Conversion Prediction and Optimization. [link](https://arxiv.org/pdf/2503.23303)
* [arXiv] CSI: Towards Personalized Conversational Sales Agents: Contextual User Profiling for Strategic Action. [link](https://arxiv.org/pdf/2504.08754)
* [arXiv] AI-Salesman: Towards Reliable Large Language Model Driven Telemarketing. [link](https://www.arxiv.org/pdf/2511.12133)
* [IWSDS 2025] Exploring Personality-Aware Interactions in Salesperson Dialogue Agents. [link](https://aclanthology.org/2025.iwsds-1.6.pdf)

#### Platform-Agent

* [ACM Transactions on Information Systems 2025] Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations. [link](https://arxiv.org/pdf/2308.16505)
* [arXiv] Beyond Retrieval-Ranking: A Multi-Agent Cognitive Decision Framework for E-Commerce Search (MACDF). [link](https://arxiv.org/pdf/2510.20567)
* [arXiv] DiMA: An LLM-Powered Ride-Hailing Assistant at DiDi. [link](https://arxiv.org/pdf/2503.04768v3)

---

### Decision

#### Consumer-Agent

* [ACL 2025] Personal Travel Solver: A Preference-Driven LLM-Solver System for Travel Planning. [link](https://aclanthology.org/2025.acl-long.1339.pdf)
* [Amazon 2024] Help Me Decide: AI-powered product comparison on Amazon. [link](https://www.aboutamazon.com/news/retail/amazon-things-to-buy-help-me-decide-gen-ai)

---


### Transaction

#### Payment-Agent

* [arXiv] Secure Autonomous Agent Payments: Verifying Authenticity and Intent in a Trustless Environment. [link](https://arxiv.org/pdf/2511.15712)
* [Google Cloud] Powering AI commerce with the new Agent Payments Protocol (AP2). [link](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol)
* [GitHub] Zen7 Payment Agent: A Dedicated Payment Network. [link](https://github.com/Zen7-Labs/Zen7-Payment-Agent)
* [arXiv] CASE: An Agentic AI Framework for Enhancing Scam Intelligence in Digital Payments. [link](https://arxiv.org/pdf/2508.19932)
* [Skyfire] KYA & Payments for Agents. [link](https://skyfire.xyz/product/)

---

### Fulfillment

#### Supply-Side Agent

* [CoRL 2023] RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control. [link](https://arxiv.org/pdf/2307.15818)
* [arXiv] RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots. [link](https://arxiv.org/pdf/2406.02523)
* [arXiv] L3MVN: Leveraging Large Language Models for Visual Target Navigation. [link](https://arxiv.org/pdf/2304.05501)
* [arXiv] Mobility VLA: Multimodal Instruction Navigation with Long-Context VLMs and Topological Graphs. [link](https://arxiv.org/pdf/2407.07775)
* [ICRA Workshop 2025] Task Planning for Mobile Manipulation in Retail Stores using Foundation Models with Iterative Re-planning. [link](https://dyalab.mines.edu/2025/icra-workshop/18.pdf)
* [Sustainability 2025] Research on Composite Robot Scheduling and Task Allocation for Warehouse Logistics Systems. [link](https://www.mdpi.com/2071-1050/17/11/5051)
* [arXiv] Physics-Aware Robotic Palletization with Online Masking Inference. [link](https://arxiv.org/pdf/2502.13443)
* [arXiv] Agentic AI Framework for Smart Inventory Replenishment. [link](https://www.arxiv.org/pdf/2511.23366)
* [arXiv] Leveraging LLM-Based Agents for Intelligent Supply Chain Planning. [link](https://arxiv.org/pdf/2509.03811)
* [arXiv] RoboFactory: Exploring Embodied Agent Collaboration with Compositional Constraints. [link](https://arxiv.org/pdf/2503.16408)
* [arXiv] Safe Human Robot Navigation in Warehouse Scenario. [link](https://arxiv.org/pdf/2503.21141)
* [TRC 2025] Agentic Large Language Models for day-to-day route choices (LLMTraveler). [link](https://trid.trb.org/View/2597138)

---

### Service

#### Consumer-Agent

*No canonical benchmark/paper list yet in the survey; contributions welcome.*

#### Platform-Agent

* [arXiv] Higher Satisfaction, Lower Cost: A Technical Report on How LLMs Revolutionize Meituan's Intelligent Interaction Systems. [link](https://arxiv.org/pdf/2510.13291)
* [arXiv] MindFlow+: A Self-Evolving Agent for E-Commerce Customer Service. [link](https://arxiv.org/pdf/2507.18884)

---

## Part II: Applications & Protocols

### Retail Shopping & Personal Assistants

* [OpenAI] Shopping Research in ChatGPT. [link](https://openai.com)
* [OpenAI] Buy it in ChatGPT. [link](https://developers.openai.com)
* [Perplexity] Shop like a Pro. [link](https://perplexity.ai)
* [Amazon] Rufus: AI Shopping Assistant. [link](https://aboutamazon.com)
* [Amazon 2025] Buy for Me. [link](https://www.aboutamazon.com/news/retail/amazon-shopping-app-buy-for-me-brands)
* [arXiv] What Is Your AI Agent Buying? Evaluation, Implications, and Emerging Questions for Agentic E-Commerce. [link](https://arxiv.org/pdf/2508.02630)
* [arXiv] PAARS: Persona Aligned Agentic Retail Shoppers. [link](https://arxiv.org/pdf/2503.24228)
* [NeurIPS 2022] WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents. [link](https://arxiv.org/pdf/2207.01206)
* [arXiv] Flippi: End To End GenAI Assistant for E-Commerce. [link](https://arxiv.org/pdf/2507.05788)
* [arXiv] iAgent: LLM Agent as a Shield between User and Recommender Systems. [link](https://arxiv.org/pdf/2502.14662)
* [arXiv] Intelligent Virtual Assistants with LLM-based Process Automation. [link](https://arxiv.org/pdf/2312.06677)
* [CVPR 2024] Wear-Any-Way: Manipulable Virtual Try-on via Sparse Correspondence Alignment. [link](https://arxiv.org/pdf/2403.12965)
* [CVPR 2024] FashionPose: Text to Pose to Relight Image Generation for Personalized Fashion Visualization. [link](https://arxiv.org/pdf/2403.12965)
* [arXiv] TravelAgent: An AI Assistant for Personalized Travel Planning. [link](https://arxiv.org/pdf/2409.08069)
* [arXiv] DeepTravel: An End-to-End Agentic Reinforcement Learning Framework for Autonomous Travel Planning Agents. [link](https://arxiv.org/pdf/2509.21842)
* [EMNLP 2025] RETAIL: Towards Real-world Travel Planning for Large Language Models. [link](https://aclanthology.org/2025.emnlp-main.752.pdf)
* [ACL 2025] Personal Travel Solver: A Preference-Driven LLM-Solver System for Travel Planning. [link](https://aclanthology.org/2025.acl-long.1339.pdf)
* [arXiv] Build Agent Advocates, Not Platform Agents. [link](https://arxiv.org/pdf/2505.04345)

### Marketplaces (C2C / P2P)

* [arXiv] FaMA: LLM-Empowered Agentic Assistant for Consumer-to-Consumer Marketplace. [link](https://arxiv.org/pdf/2509.03890v1)
* [arXiv] FishBargain: An LLM-Empowered Bargaining Agent for Online Fleamarket Platform Sellers. [link](https://arxiv.org/pdf/2502.10406)
* [arXiv] The Automated but Risky Game: Modeling Agent-to-Agent Negotiations and Transactions in Consumer Markets. [link](https://arxiv.org/pdf/2506.00073v3)

### Advertising, Bidding & Merchant Growth

* [arXiv] RTBAgent: A LLM-based Agent System for Real-Time Bidding. [link](https://arxiv.org/pdf/2502.00792)
* [arXiv] Agentic Multimodal AI for Hyper-Personalized B2B and B2C Advertising in Competitive Markets: An AI-Driven Competitive Advertising Framework. [link](https://arxiv.org/pdf/2504.00338)
* [arXiv] CAL-RAG: Retrieval-Augmented Multi-Agent Generation for Content-Aware Layout Design. [link](https://arxiv.org/pdf/2506.21934)
* [EMNLP Industry 2024] IPL: Leveraging Multimodal Large Language Models for Intelligent Product Listing. [link](https://aclanthology.org/2024.emnlp-industry.52.pdf)

### Sales & Customer Service

* [Amazon] Seller Assistant. [link](https://aboutamazon.com)
* [arXiv] MindFlow+: A Self-Evolving Agent for E-Commerce Customer Service. [link](https://arxiv.org/pdf/2507.18884)
* [EMNLP Findings 2025] Towards Personalized Conversational Sales Agents: Contextual User Profiling for Strategic Action. [link](https://aclanthology.org/2025.findings-emnlp.275.pdf)
* [arXiv] AI-Salesman: Towards Reliable Large Language Model Driven Telemarketing. [link](https://www.arxiv.org/pdf/2511.12133)
* [IWSDS 2025] Exploring Personality-Aware Interactions in Salesperson Dialogue Agents. [link](https://aclanthology.org/2025.iwsds-1.6.pdf)
* [arXiv] SalesRLAgent: A Reinforcement Learning Approach for Real-Time Sales Conversion Prediction and Optimization. [link](https://arxiv.org/pdf/2503.23303)

### Recommendation & Search Systems

* [SIGIR 2024] MACRec: A Multi-Agent Collaboration Framework for Recommendation. [link](https://dl.acm.org/doi/abs/10.1145/3626772.3657669)
* [arXiv] ARAG: Agentic Retrieval Augmented Generation for Personalized Recommendation. [link](https://arxiv.org/pdf/2506.21931)
* [arXiv] RecMind: Large Language Model Powered Agent For Recommendation. [link](https://arxiv.org/pdf/2308.14296)
* [arXiv] CARTS: Collaborative Agents for Recommendation Textual Summarization. [link](https://arxiv.org/pdf/2506.17765)
* [SIGIR 2024] Let Me Do It For You: Towards LLM Empowered Recommendation via Tool Learning. [link](https://dl.acm.org/doi/abs/10.1145/3626772.3657828)
* [arXiv] AgentCF: Collaborative Learning with Autonomous Language Agents for Recommender Systems. [link](https://arxiv.org/pdf/2310.09233)
* [ACM Transactions on Information Systems 2025] Recommender AI Agent: Integrating Large Language Models for Interactive Recommendations. [link](https://arxiv.org/pdf/2308.16505)
* [SIGIR 2024] On Generative Agents in Recommendation. [link](https://dl.acm.org/doi/pdf/10.1145/3626772.3657844)
* [WWW 2025] LREF: A Novel LLM-based Relevance Framework for E-commerce Search. [link](https://dl.acm.org/doi/pdf/10.1145/3701716.3715246)
* [ACL Industry 2025] User Feedback Alignment for LLM-powered Exploration in Large-scale Recommendation Systems. [link](https://aclanthology.org/2025.acl-industry.70.pdf)
* [arXiv] LORE: A Large Generative Model for Search Relevance. [link](https://arxiv.org/pdf/2512.03025)
* [WSDM 2025] Enhancing E-Commerce Query Rewriting: A Large Language Model Approach with Domain-Specific Pre-Training and Reinforcement Learning. [link](https://dl.acm.org/doi/epdf/10.1145/3627673.3680109)
* [arXiv] Beyond Retrieval-Ranking: A Multi-Agent Cognitive Decision Framework for E-Commerce Search. [link](https://arxiv.org/pdf/2510.20567)
* [arXiv] LocalSearchBench: Benchmarking Agentic Search in Real-World Local Life Services. [link](https://www.arxiv.org/pdf/2512.07436)
* [arXiv] LocalGPT: Benchmarking and Advancing Large Language Models for Local Life Services in Meituan. [link](https://arxiv.org/pdf/2506.02720)
* [KDD 2023] NEON: Living Needs Prediction System in Meituan. [link](https://arxiv.org/pdf/2307.16644)
* [arXiv] Higher Satisfaction, Lower Cost: A Technical Report on How LLMs Revolutionize Meituan's Intelligent Interaction Systems. [link](https://arxiv.org/pdf/2510.13291)
* [arXiv] Enterprise Deep Research: Steerable MultiAgent Deep Research for Enterprise Analytics. [link](https://arxiv.org/pdf/2510.17797)

### Platform Services & Enterprise Solutions

* [OpenAI] Operator. [link](https://openai.com/index/introducing-operator/)
* [Adobe] Adobe Experience Platform Agent Orchestrator. [link](https://business.adobe.com)
* [Salesforce] Artificial Intelligence (AI) at Salesforce. [link](https://salesforce.com)

### Mobility & On-demand Services

* [arXiv] DiMA: An LLM-Powered Ride-Hailing Assistant at DiDi. [link](https://arxiv.org/pdf/2503.04768v3)
* [arXiv] RideAgent: An LLM-Enhanced Optimization Framework for Automated Taxi Fleet Operations. [link](https://arxiv.org/pdf/2505.06608)

### Unmanned Stores & Autonomous Retail

* [Wikipedia] Amazon Go. [link](https://en.wikipedia.org/wiki/Amazon_Go)
* [arXiv] A Survey of Challenges and Sensing Technologies in Autonomous Retail Systems. [link](https://arxiv.org/pdf/2503.07997)
* [Nature Scientific Reports 2024] Smart customer service in unmanned retail store enhanced by large language model. [link](https://www.nature.com/articles/s41598-024-71089-9)

### Intelligent Cockpit & In-Vehicle Commerce

* [SoundHound 2025] CES 2025: SoundHound AI Debuts Its First Ever In-Vehicle Voice Assistant With On-The-Go Food Ordering. [link](https://www.soundhound.com/newsroom/press-releases/ces-2025-soundhound-ai-debuts-its-first-ever-in-vehicle-voice-assistant-with-on-the-go-food-ordering)
* [Alibaba Cloud 2025] Alibaba Unveils Intelligent Cockpits, Enterprise Partnerships and AI Glasses at WAIC 2025. [link](https://www.alibabacloud.com/blog/alibaba-unveils-intelligent-cockpits-enterprise-partnerships-and-ai-glasses-at-waic-2025_602409)

### Supply Chain, Warehousing & Embodied Commerce

* [CoRL 2023] RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control. [link](https://arxiv.org/pdf/2307.15818)
* [arXiv] RoboCasa: Large-Scale Simulation of Everyday Tasks for Generalist Robots. [link](https://arxiv.org/pdf/2406.02523)
* [ICRA Workshop 2025] Task Planning for Mobile Manipulation in Retail Stores using Foundation Models with Iterative Re-planning. [link](https://dyalab.mines.edu/2025/icra-workshop/18.pdf)
* [Sustainability 2025] Research on Composite Robot Scheduling and Task Allocation for Warehouse Logistics Systems. [link](https://www.mdpi.com/2071-1050/17/11/5051)
* [arXiv] Physics-Aware Robotic Palletization with Online Masking Inference. [link](https://arxiv.org/pdf/2502.13443)
* [arXiv] Agentic AI Framework for Smart Inventory Replenishment. [link](https://www.arxiv.org/pdf/2511.23366)
* [arXiv] Leveraging LLM-Based Agents for Intelligent Supply Chain Planning. [link](https://arxiv.org/pdf/2509.03811)
* [arXiv] RoboFactory: Exploring Embodied Agent Collaboration with Compositional Constraints. [link](https://arxiv.org/pdf/2503.16408)
* [arXiv] L3MVN: Leveraging Large Language Models for Visual Target Navigation. [link](https://arxiv.org/pdf/2304.05501)
* [arXiv] Mobility VLA: Multimodal Instruction Navigation with Long-Context VLMs and Topological Graphs. [link](https://arxiv.org/pdf/2407.07775)
* [arXiv] IndustryEQA: Pushing the Frontiers of Embodied Question Answering in Industrial Scenarios. [link](https://arxiv.org/pdf/2505.20640)
* [arXiv] AssistantX: An LLM-Powered Proactive Assistant in Collaborative Human-Populated Environments. [link](https://arxiv.org/pdf/2409.17655)
* [arXiv] Multi-Agent Reinforcement Learning for Dynamic Pricing in Supply Chains: Benchmarking Strategic Agent Behaviours under Realistically Simulated Market Conditions. [link](https://arxiv.org/pdf/2507.02698)
* [arXiv] Safe Human Robot Navigation in Warehouse Scenario. [link](https://arxiv.org/pdf/2503.21141)
* [Amazon] Amazon has more than 1 million robots that sort, lift, and carry packages—see them in action. [link](https://www.aboutamazon.com/news/operations/amazon-robotics-robots-fulfillment-center)

### Negotiation & Pricing

* [arXiv] How Well Can LLMs Negotiate? NegotiationArena Platform and Analysis. [link](https://arxiv.org/pdf/2402.05863)
* [arXiv] Advancing AI Negotiations: New Theory and Evidence from a Large-Scale Autonomous Negotiation Competition. [link](https://arxiv.org/pdf/2503.06416)
* [arXiv] CompeteAI: Understanding the Competition Dynamics of Large Language Model-based Agents. [link](https://arxiv.org/pdf/2310.17512)

### Protocols & Standards

* [Model Context Protocol] Model Context Protocol (MCP). [link](https://modelcontextprotocol.io)
* [Agent2Agent Protocol] Agent2Agent (A2A) Protocol. [link](https://a2a-protocol.org)
* [OpenAI] Agentic Commerce Protocol (ACP). [link](https://github.com/openai/agentic-commerce-protocol)
* [W3C 2025] Verifiable Credentials 2.0 family of specifications. [link](https://www.w3.org/news/2025/the-verifiable-credentials-2-0-family-of-specifications-is-now-a-w3c-recommendation/)
* [arXiv] Agent TCP/IP: An Agent-to-Agent Transaction System. [link](https://arxiv.org/pdf/2501.06243)
* [arXiv] Building A Secure Agentic AI Application Leveraging Google's A2A Protocol. [link](https://arxiv.org/pdf/2504.16902)

### Payment & Transaction Protocols

* [arXiv] Secure Autonomous Agent Payments: Verifying Authenticity and Intent in a Trustless Environment. [link](https://arxiv.org/pdf/2511.15712)
* [Google Cloud] Powering AI commerce with the new Agent Payments Protocol (AP2). [link](https://cloud.google.com/blog/products/ai-machine-learning/announcing-agents-to-payments-ap2-protocol)
* [Skyfire] KYA & Payments for Agents. [link](https://skyfire.xyz/product/)
* [GitHub] MachinePal – x402 AI Payment Agent for Any Website or API. [link](https://github.com/skalenetwork/machinepal)
* [GitHub] Zen7 Payment Agent: A Dedicated Payment Network. [link](https://github.com/Zen7-Labs/Zen7-Payment-Agent)
* [arXiv] CASE: An Agentic AI Framework for Enhancing Scam Intelligence in Digital Payments. [link](https://arxiv.org/pdf/2508.19932)

---

## Part III: Benchmarks

* [arXiv] ShoppingBench: A Real-World Intent-Grounded Shopping Benchmark for LLM-based Agents. [link](https://arxiv.org/pdf/2508.04266)
* [arXiv] DeepShop: A Benchmark for Deep Research Shopping Agents. [link](https://arxiv.org/pdf/2506.02839)
* [NeurIPS 2022] WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents. [link](https://arxiv.org/pdf/2207.01206)
* [arXiv] LocalSearchBench: Benchmarking Agentic Search in Real-World Local Life Services. [link](https://www.arxiv.org/pdf/2512.07436)
* [arXiv] LocalGPT: Benchmarking and Advancing Large Language Models for Local Life Services in Meituan. [link](https://arxiv.org/pdf/2506.02720)
* [arXiv] Magentic Marketplace: An Open-Source Environment for Studying Agentic Markets. [link](https://arxiv.org/pdf/2510.25779)
* [ACL Industry 2025] SimUSER: Simulating User Behavior with Large Language Models for Recommender System Evaluation. [link](https://aclanthology.org/2025.acl-industry.5.pdf)
* [arXiv] EcomBench: Towards Holistic Evaluation of Foundation Agents in E-commerce. [link](https://arxiv.org/pdf/2512.08868)
* [arXiv] What Is Your AI Agent Buying? Evaluation, Implications, and Emerging Questions for Agentic E-Commerce. [link](https://arxiv.org/pdf/2508.02630)
* [arXiv] Multi-Agent Reinforcement Learning for Dynamic Pricing in Supply Chains: Benchmarking Strategic Agent Behaviours under Realistically Simulated Market Conditions. [link](https://arxiv.org/pdf/2507.02698)
* [arXiv] How Well Can LLMs Negotiate? NegotiationArena Platform and Analysis. [link](https://arxiv.org/pdf/2402.05863)
* [arXiv] LLM Agent Meets Agentic AI: Can LLM Agents Simulate Customers to Evaluate Agentic-AI-based Shopping Assistants? [link](https://arxiv.org/pdf/2509.21501)
* [arXiv] $\tau^2$-Bench: Evaluating Conversational Agents in a Dual-Control Environment. [link](https://arxiv.org/pdf/2506.07982)
* [ICLR 2026] VitaBench: Benchmarking LLM Agents with Versatile Interactive Tasks in Real-world Applications. [link](https://arxiv.org/pdf/2509.26490)
---

## Contributing

Contributions are welcome! Please submit a Pull Request following the format:

- `[Venue Year] Paper Title. [link](url)`

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
