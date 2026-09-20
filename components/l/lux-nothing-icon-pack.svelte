<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="ceu-4923b"/><circle class="xyhhj5b6q"/><circle class="smh8hwt4g"/><circle class="tbqc6tb1l"/><circle class="ll1-3kw5m"/><path class="eom_l4g3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:lux-nothing-icon-pack" {...props}></Icon>
<style>
:global(.ceu-4923b) {
  cx: 10.5px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.eom_l4g3d) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 19za5 5 0 0 1 5 5v13.5a5 5 0 0 1-10 0V24a5 5 0 0 1 5-5m27-13.5za5 5 0 0 1 5 5V24a5 5 0 0 1-10 0V10.5a5 5 0 0 1 5-5");
}

:global(.ll1-3kw5m) {
  cx: 37.5px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.smh8hwt4g) {
  cx: 24px;
  cy: 24px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tbqc6tb1l) {
  cx: 24px;
  cy: 37.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xyhhj5b6q) {
  cx: 24px;
  cy: 10.5px;
  r: 5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
