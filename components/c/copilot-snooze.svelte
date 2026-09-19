<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc78nobou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dc78nobou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:copilot-snooze" {...props}></Icon>
