<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yuv4zy4xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:crop-9-16-sharp" {...props}></Icon>
<style>
:global(.yuv4zy4xa) {
  fill: currentColor;
  d: path("M8 20V4h8v16z");
}

</style>
