<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qdvztpbtq"/><path class="a7nxe7_tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:caribbean" {...props}></Icon>
<style>
:global(.a7nxe7_tm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.268L16.907 24L24 33.732");
}

:global(.qdvztpbtq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.923 6.743H18.516L31.093 24L18.516 41.257h11.407L42.5 24zM18.077 41.257L5.5 24L18.077 6.743");
}

</style>
