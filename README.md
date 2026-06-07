# A/B test of Gaming Dataset with Python and Tableau

## Business problem
The company rolled out a new in-game monetization feature to a subset of users (Group B), while the rest remained on the old version (Group A).
The goal is to evaluate whether the new feature improves monetization without negatively affecting user engagement.

## Hypotheses
### Prymary hypothesis
Users exposed to the new feature (Group B) generate higher revenue compared to the control group (Group A).

### Secondary hypothesis
The new feature increases the proportion of paying users (conversion rate).

### Guardrail hypothesis
The new feature does not negatively impact user activity.

## Define metrics
ARPU (Average Revenue Per User)
Conversion rate (payer rate)
ARPPU (optional but strong)
”
🛡 3. Guardrail metric (super important)
👉 Engagement proxy

Since you don’t have session length:

👉 Use number of logins per user
