<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="xl7qmnbkh"/><rect class="chhoomerj"/><rect class="hvzqn00lz"/><circle class="vpznabclk"/><circle class="yc7k2bh1j"/><circle class="sd1m56bxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:agenda" {...props}></Icon>
<style>
:global(.chhoomerj) {
  width: 31px;
  height: 8.5px;
  x: 8.5px;
  y: 17.125px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

:global(.hvzqn00lz) {
  width: 31px;
  height: 14px;
  x: 8.5px;
  y: 29.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

:global(.sd1m56bxt) {
  cx: 34.75px;
  cy: 33.75px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.vpznabclk) {
  cx: 34.75px;
  cy: 9px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xl7qmnbkh) {
  width: 31px;
  height: 8.5px;
  x: 8.5px;
  y: 4.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1px;
}

:global(.yc7k2bh1j) {
  cx: 34.75px;
  cy: 21.375px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
