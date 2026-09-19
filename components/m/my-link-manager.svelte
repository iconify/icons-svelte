<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="ha89l6blz"/><path class="ee7asubho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:my-link-manager" {...props}></Icon>
<style>
:global(.ee7asubho) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.757 12.082v25.544a4 4 0 0 0 4 4h25.544m3.307-32.851h-9.081v15.749l4.541-2.811l4.54 2.811z");
}

:global(.ha89l6blz) {
  width: 30.766px;
  height: 30.766px;
  x: 11.991px;
  y: 4.626px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
