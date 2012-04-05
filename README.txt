Readme file for the Invite link module for Drupal
---------------------------------------------

Description:
Provides the invite link for invite module. Link can be used on external
sites and clicked by unlimited visitors.
When someone registers, invitation is treated like sent from invite module.

Link is described as follows:
http://#yoursite/invite/code/#inviter_id

where
#yoursite - is your site address
#inviter_id - is user id (uid)

Module can be very useful if used with userpoints_invite module
(for example, the user can paste the invite link on the external sites and
gain points more efficiently).

Dependencies:
Invite (required) - http://drupal.org/project/invite
User Points Invite (optional, described below) -
http://drupal.org/project/userpoints_contrib

Installation:
Extract the 'invite_link' folder from the tar ball to the modules
directory from your website (typically sites/all/modules).

Usage:
After installation a new tab is added to invite tabs (user/%user/invites/link)
- where user can see and copy his personal link.
