<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-l9phbwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y-l9phbwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chat-16" {...props}></Icon>
