<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux7dz1b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ux7dz1b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:draw-polygon" {...props}></Icon>
