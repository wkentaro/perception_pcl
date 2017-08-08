- ``~max_queue_size`` (int, default: ``3``)

  Queue size of each subscriber, and synchronization of subscribers.

- ``~use_indices`` (bool, default: ``false``)

  If ``true``, the topic ``~indices`` is subscribed.

- ``~latched_indices`` (bool, default: ``false``)

  If ``true``, we assume input `~indices` topic is latched.

- ``~approximate_sync`` (bool, default: ``false``)

  If ``true``, approximate time synchronization policy is used
  for the synchronization of ``~input`` and ``~indices``,
