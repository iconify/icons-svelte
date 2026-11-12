<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l48yp7bmv.css';
import '../../css/t/tmnz0vbmc.css';
import '../../css/r/r4qkfrbth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l48yp7bmv"/><path class="tmnz0vbmc"/><path class="r4qkfrbth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:paypal-dark" {...props}></Icon>
