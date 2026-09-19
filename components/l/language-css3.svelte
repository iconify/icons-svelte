<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-f_web7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":400};
const content = `<path class="i-f_web7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:language-css3" {...props}></Icon>
