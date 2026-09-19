<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="xiu-zs_4m"/><circle class="kguly92mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:neutron-recorder" {...props}></Icon>
<style>
:global(.kguly92mf) {
  cx: 24px;
  cy: 24px;
  r: 7.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xiu-zs_4m) {
  width: 39px;
  height: 26px;
  x: 4.386px;
  y: 10.876px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5px;
  ry: 5px;
}

</style>
