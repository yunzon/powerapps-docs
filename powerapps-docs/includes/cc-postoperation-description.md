Occurs after the main system operation and within the database transaction.<br /><br />Use this stage to modify any properties of the message before it is returned to the caller.<br /><br />Avoid applying changes to an entity included in the message because this will trigger a new Update event.