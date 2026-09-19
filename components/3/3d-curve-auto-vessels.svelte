<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxjnpbb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxjnpbb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:3d-curve-auto-vessels" {...props}></Icon>
