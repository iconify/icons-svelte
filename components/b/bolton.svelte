<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vs4-zf5xr"/><circle class="kguly92mf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:bolton" {...props}></Icon>
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

:global(.vs4-zf5xr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.75 5.38h-21.5L2.5 24l10.75 18.62h21.5L45.5 24z");
}

</style>
