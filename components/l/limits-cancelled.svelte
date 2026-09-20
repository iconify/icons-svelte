<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khxp_lblc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="khxp_lblc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:limits-cancelled" {...props}></Icon>
