<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtynt79qx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="rtynt79qx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:invert-colors-off" {...props}></Icon>
