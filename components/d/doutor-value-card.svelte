<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vm6ya0rbd"/><rect class="jx4hcl6sj"/><path class="y_n1ecb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:doutor-value-card" {...props}></Icon>
<style>
:global(.jx4hcl6sj) {
  width: 30.5px;
  height: 19.5px;
  x: 13px;
  y: 17.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
  ry: 2px;
}

:global(.vm6ya0rbd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.875 17.25v-6m-6.125 6v-6M13 30.75H6.5c-1.108 0-2-.892-2-2v-15.5c0-1.108.892-2 2-2H33c1.108 0 2 .892 2 2v4");
}

:global(.y_n1ecb7q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.375 36.75v-19.5m-6.125 19.5v-19.5");
}

</style>
