# Core Beliefs

## We believe that we should take an iterative approach to engineering, setting, and achieving multiple smaller goals instead of one goal to complete the entire project.

This is demonstrated through the way we design solutions, and how we implement them in our day-to-day activities.

- We use an Agile Methodology.
  - Fill a Product Backlog with user stories.
  - Estimate the “cost” of those user stories.
  - Execute on user stories in a “sprint”.
    - One weeklong sprint.
    - Take user stories from the Product Backlog and put them in the Sprint Backlog.
      - Based on “cost” of user stories and the estimated “cost capacity” of each engineer.
    - Assign and execute on user stories from Sprint Backlog during sprint.
    - Conduct a retrospective at the end of the sprint.
      - Evaluates what went well, didn’t go well, and what can be improved.
    - Add new user stories to the Product Backlog and “cost” them as a team.
- We design with the understanding that code will change in the future.
  - Solve the problem we need knows to be solved now, not the problem we speculate might be needed to be solved in the future.
    - “When the future problem needs to be solved, it is easier to see it’s actual shape and requirements in the physical universe.”
  - Design for features to be added incrementally instead of all at once.
- We gain buy in from our customers about having an incremental approach to development.
  - We are transparent about how we plan to incrementally reach the final solution.
  - We explain the benefits of an incremental approach.
  - We work with the customer to prioritize which features should be completed first.

## We believe that all the work we do is for the team and the project, not owned by an individual but for a common shared goal.

This is demonstrated through the way we discuss and analyze the design and implementation of the different feature areas of our project.

- We produce code that is readable and consistent.
  - Follows a Style Guide agreed upon by the team at the start of a project.
  - We take advantage of tools such as linters and style checkers to automate and save time doing this.
- We peer review all code that is produced.
  - We follow methodologies described in the Code With Engineering Playbook and it’s recommended resources such as the Google Engineering Practices documentation for how to do a code review.
    - We look for the same things in each code review.
    - We are empathetic and understand the social aspects of giving feedback. 

## We believe that we should compromise long term usability for short term deadlines only when needed.

This is demonstrated through our adherence to our Engineering Fundamentals in ordinary circumstances and our willingness to deviate from them only when necessary.

- We only compromise on our Engineering Fundamentals when following them would result in a missed deadline.
  - We discuss whether this is necessary in every case, such as on a per-user story or per-bug basis.
  - We file the known deficiencies we are introducing into the project as bugs or user stories to be completed as soon as possible.
- We are transparent with the customer about the trade-offs of taking this approach.
  - We explain the introduced deficiencies or technical debt and our plan to address it in the future.
  - We discuss the flexibility of future deadlines so that we avoid having to make the same compromises again.

## We believe that we should demonstrate (to each other and the customer) our commitment to creating a collaborative and efficient team dynamic.

This is demonstrated through our attitude towards one another and our proactiveness towards fostering a growth mindset.

- We welcome conversations about how feedback is being given.
  - We can have a “meta” conversation about how we are giving or receiving feedback with the other person.
    - Our goal is to find the best ways to communicate.
  - We are empathetic and understanding when giving feedback.
    - We understand the social aspects and aim to give feedback in a way where the receiver will be the most receptive to the feedback we are giving.
    - We try to be aware of how the receiver is receiving our feedback and whether we should change how we are providing it.
  - We are cognizant and aware of our unconscious reactions when we receive feedback.
    - We use mindfulness and self-awareness techniques to notice when we feel defensive or uncomfortable when receiving feedback.
    - We remind ourselves that the provider has our best interests in mind.
- We conduct design feedback sessions where we present, solicit feedback, and/or have discussions on a proposed design.
  - We value and consider all voices and opinions in our design sessions.
  - We encourage the customer and every person to be involved whether it be by providing feedback or conducting their own session.

## We believe that we should maximize the amount of time people have to create, whether that be design, coding, etc.

This is demonstrated through our commitment to maximizing each developers “focus time” and enabling developers to “do” as quick as possible.

- We use automation as much as possible.
  - We find ways of automating often repeated processes in a developer’s day.
  - We automate build and test pipelines.
  - We avoid situations where a developer must manually do something that cannot be done programmatically.
- We document what we do as we do it.
  - We write onboarding documentation as early as possible.
  - We document design discussions and decisions inside of the repository.
- We aim to make meetings as efficient as possible.
  - We reduce the quantity and duration of formal “all-hands” meetings.
    - Such as sprint “overhead” meetings.
  - We always have an agenda and a desired outcome for a meeting that is communicated prior to the meeting.
  - We advocate for meetings to be kept on track and to do our best helping each other moderate meetings to keep them on-topic and utilizing the most of each participant’s time.

## We believe that we should handle customer data with the upmost caution and safety.

This is demonstrated through our communication and proactive thought around how to safely store and handle customer data.

- We have conversations with the customer about what sort of data will be used in the project.
  - We determine the sensitivity of the data and what would need to happen if that data were to be accidentally deleted, overwritten, lost, or improperly published.
- We ensure that any sensitive data is backed up or stored in a redundant way.
- We respect any agreements we’ve made with the customer to not view or use any sensitive data, even if we have access to it.

## We believe that we should design and implement with reusability and sharing in mind.

This is demonstrated through our forethought on how we can apply known patterns to our solutions, and reuse or share parts of our solution with others.

- We research known solutions and patterns that may save time and reduce complexity of our solutions in the design and implementation phases.
  - We leverage public resources as well as internal CSE resources such as the Solutions Area Tech Domains, other Dev Teams, and Subject Matter Experts (SME’s.)
- We share our solutions within CSE to see if any other Dev Teams or Tech Domains will find it beneficial.
  - This is done especially when we were unable to find a similar solution internally.
