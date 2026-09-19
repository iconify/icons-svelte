<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xsq3reb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xsq3reb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:behance-square" {...props}></Icon>
