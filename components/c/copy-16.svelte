<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3frkwgdc.css';
import '../../css/i/irv6a3b8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y3frkwgdc"/><path class="irv6a3b8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:copy-16" {...props}></Icon>
