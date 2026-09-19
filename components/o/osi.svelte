<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mut20k02r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mut20k02r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:osi" {...props}></Icon>
