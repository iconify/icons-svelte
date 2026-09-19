<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l5fmf7b_i"/><path class="z78mcuald"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:githo" {...props}></Icon>
<style>
:global(.l5fmf7b_i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24a21.478 21.478 0 1 0-1.01 6.529");
}

:global(.z78mcuald) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.453 32.444l5.038-1.915l1.915 5.037");
}

</style>
