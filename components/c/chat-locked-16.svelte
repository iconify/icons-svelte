<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxex4oboi.css';
import '../../css/i/i-lfmccxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mxex4oboi"/><path class="i-lfmccxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:chat-locked-16" {...props}></Icon>
