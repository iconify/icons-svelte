<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw2r7sb3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":432};
const content = `<path class="uw2r7sb3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:paypal" {...props}></Icon>
