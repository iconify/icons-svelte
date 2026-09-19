<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="fcyco1mit"/><path class="v9dmbdbwq"/><circle class="rudkgengt"/><path class="hszo_acky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lineage-camera" {...props}></Icon>
<style>
:global(.fcyco1mit) {
  cx: 27.238px;
  cy: 26.437px;
  r: 12.652px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.hszo_acky) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.581 15.203V37.76");
}

:global(.rudkgengt) {
  cx: 8.243px;
  cy: 19.821px;
  r: 1.373px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v9dmbdbwq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.887 37.76h7.7a2.913 2.913 0 0 0 2.913-2.913v-15.04a4.57 4.57 0 0 0-2.928-4.268l-4.647-1.792c-.372-3.932-2.807-4.835-2.807-4.835H21.421s-2.435.903-2.807 4.834L8.147 15.914A4.574 4.574 0 0 0 4.5 20.392v14.455a2.913 2.913 0 0 0 2.913 2.913H21.59");
}

</style>
