<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr7avqm6c.css';
import '../../css/r/rhx6aqb6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr7avqm6c"/><path class="rhx6aqb6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:question-light" {...props}></Icon>
