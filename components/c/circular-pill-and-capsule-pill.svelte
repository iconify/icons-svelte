<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-8x0x0fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="m-8x0x0fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:circular-pill-and-capsule-pill" {...props}></Icon>
