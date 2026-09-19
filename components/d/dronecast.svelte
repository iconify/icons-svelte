<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fjelj-byq"/><path class="zy6sgn2pa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dronecast" {...props}></Icon>
<style>
:global(.fjelj-byq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.74 30.7L6.5 42.43L24 5.57m4.26 25.13L41.5 42.43L24 5.57");
}

:global(.zy6sgn2pa) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.74 30.7h8.52L24 5.57Z");
}

</style>
