<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jvm9wbbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="jvm9wbbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:panorama-vertical" {...props}></Icon>
