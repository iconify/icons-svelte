<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ifdw3accd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:hourglass-simple-high-fill" {...props}></Icon>
<style>
:global(.ifdw3accd) {
  fill: currentColor;
  d: path("M211.18 196.56L139.57 128l71.61-68.56a2 2 0 0 1 .13-.13A16 16 0 0 0 200 32H56a16 16 0 0 0-11.31 27.31a2 2 0 0 1 .13.13L116.43 128l-71.61 68.56a2 2 0 0 1-.13.13A16 16 0 0 0 56 224h144a16 16 0 0 0 11.32-27.31a2 2 0 0 1-.14-.13M200 48l-16.7 16H72.72L56 48ZM56 208l72-68.92L200 208Z");
}

</style>
