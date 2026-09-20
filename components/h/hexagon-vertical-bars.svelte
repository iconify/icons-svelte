<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmdj_zw-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hmdj_zw-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:hexagon-vertical-bars" {...props}></Icon>
