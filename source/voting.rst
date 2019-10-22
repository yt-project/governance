.. _voting:

############
Voting Items
############

Decisions about the future of the project are made through discussion with all
members of the community. All non-sensitive project management discussion takes
place on the project developers’ mailing list, the issue tracker, and in the
project meetings mentioned above. Occasionally, sensitive discussion occurs on
a private list, but the project defaults to open meetings.

The yt-project uses a “consensus seeking” process for making large,
project-changing decisions. This approach has a series of decision-making
fallbacks to help ensure that all contributions to the project will eventually
be decided upon. This process is summarized below. 

.. _decision-making:

The Decision-Making Process
----------------------------

#. The group has a discussion about the change and tries to find a resolution
   with no objections among project members. 

#. If no concensus can be found in the community, or if a community member
   requests it, then the community will have
   a vote in relevant channels (the mailing list, the YTEP, or both). The
   vote(s) will conclude two weeks after they have been called, and require a
   2/3 majority to pass. If both modes of voting are active (e.g. in the
   mailing list and the YTEP), a 2/3 majority in either will result in a
   passing vote. 

#. If no 2/3 majority is found in the vote(s) cast, then the decision is
   escalated to the steering committee. The steering committee will try to find
   a consensus within a month of the initial escalation in case members of 
   the steering committee are
   unable to participate in the discussion for whatever reason. 

#. If the steering committee cannot find a consensus, then they fall back to a
   majority vote. 

This is what we hereafter may refer to as “the decision making process”.

.. note:: 
   If a veto -1 vote or rejecting review is cast on a lazy consensus (e.g. on a
   documentation change where the full decision making process is not required), 
   the proposer/author can appeal to the
   community and project members and the change can be approved or rejected using
   the decision making procedure outlined above.

.. important:: 
   Project members are expected to attempt to resolve issues with
   the contributor before casting a veto vote or rejecting review. 
   Resolving issues here may be
   proposing alternative implementations, alternative language, or a variant of
   the solution that the project member feels is more workable. Project members
   are expected to use veto votes and rejecting reviews sparingly. 

Decisions (in addition to adding project members and Steering Committee
membership) are made according to the following rules:

Minor Documentation Changes
---------------------------

Minor Documentation changes, such as typo fixes, or addition / correction of a
sentence require an accepting pull request review 
by a project member, no rejecting reviews by a project member (lazy consensus). 
Project members are expected to give “reasonable time” 
to others to give their opinion on the pull
request if they’re not confident others would agree. E-mails to the development
mailing list are not required for minor documentation changes. 

.. _code-change-process:

Code Changes and Major Documentation Changes
--------------------------------------------

Code changes and major documentation changes in a pull request require approving reviews 
by two project members,
no rejecting reviews by a project member (lazy consensus). At any point in
the pull request review process a reviewer may request that the author e-mail
the development mailing list to continue the discussion outside of the pull
request. An e-mail to yt-dev is not always required for changes of this
magnitude, but it is an avenue that may be necessary to ensure that the change
is in accordance with the project style and philosophy. If the code change is
substantive enough, a member may request that the change be backed by a YTEP.  

If a change of this magnitude 
is proposed in an issue or the mailing list before a pull request is submitted, 
the project recommends  
that the issue receive positive/affirmitive feedback by at least one project
member before a PR is submitted. The submitted PR will then go through the same
requirements for merging as outlined in the first sentence of this section. 

.. note:: 
   While adding a new supporting frontend is generally a substantive contribution, 
   it does not require a YTEP and falls under this category. 

Changes to the API Principles and Changes to Dependencies or Supported Versions
-------------------------------------------------------------------------------

Changes to the API principles and changes to dependencies or supported versions
happen via a Enhancement proposals (YTEPs) and follows the decision-making
process outlined in :ref:`decision-making`. Discussions regarding these changes
will occur in both the mailing list and the YTEP, and votes may be cast in
either. 

.. note:: 
   A YTEP is only required for adding a new hard dependency. Adding an optional 
   dependency does not necessarily require a YTEP, but may be called for by a code
   reviewer if necessary. In general, code contributions that add an optional
   depencency fall under the category of :ref:`code-change-process`.

Changes to the Project Governance 
---------------------------------------

Changes to the project governance model use the same decision process outlined
in :ref:`decision-making`. These changes are high enough level to imact the
governance YTEP and the governance documentation.  

Changes to the governance documents which do not impact the high-level model
follow the same process as in :ref:`code-change-process`. These changes will
generally not affect the governance YTEP but may enhance or clarify the
existing governance documentation. 

Project Membership
------------------

**Entry** 

A member is someone who has made continued and significant contribution to the
project (changes to the codebase, discussion on mailing lists, feedback on pull
requests, documentation, teaching, etc.) for some period of time. 
After such a period, potential new members are nominated for membership by an
existing member and confirmed by positive votes from three additional members.
Nomination can happen in the yt-dev mailing list or in a team meeting. If a
nomination and vote do occur in a team meeting, the nomination and vote must be
documented in the meeting notes. 
Once a developer becomes a member, they remain a member for life. A member
maintains the option to give up their membership and have their name removed
from the list. 

**Removal** 

Finally, project membership may be revoked for anyone who is deemed to be
directly harmful to the project or the community upon a nomination by another
member and five supporting member votes. Once five supporting member votes are
reached, the member is nominated for revoked membership and the decision is
sent to the steering committee for a final vote. The vote made by the steering
committee must be equal or greater than 3/5. Revoking membership will result in a
loss of commit rights to yt project repositories and removal of membership from
project pages.

