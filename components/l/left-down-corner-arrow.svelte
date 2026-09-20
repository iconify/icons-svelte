<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/husfv7cel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="husfv7cel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:left-down-corner-arrow" {...props}></Icon>
