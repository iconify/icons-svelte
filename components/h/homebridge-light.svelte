<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_yv0yb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h_yv0yb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:homebridge-light" {...props}></Icon>
