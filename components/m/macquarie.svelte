<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="fdtk6wc4p"/><ellipse class="l7q5sobjz"/><ellipse class="hube3yb9m"/><circle class="xakrkvy8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:macquarie" {...props}></Icon>
<style>
:global(.fdtk6wc4p) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 21.5px;
  ry: 19.75px;
}

:global(.hube3yb9m) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12px;
  ry: 10.5px;
}

:global(.l7q5sobjz) {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 18.5px;
  ry: 19.75px;
}

:global(.xakrkvy8r) {
  cx: 24px;
  cy: 24px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
