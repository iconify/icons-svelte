<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="jc1oydeao"/><path class="sl4_z-bki"/><circle class="hmizyiyip"/><circle class="zj59rjbnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cartaocontinente" {...props}></Icon>
<style>
:global(.hmizyiyip) {
  cx: 24px;
  cy: 24px;
  r: 8.622px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jc1oydeao) {
  width: 39px;
  height: 31px;
  x: 4.5px;
  y: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.sl4_z-bki) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.202 26.816a3.43 3.43 0 0 1-2.976 1.726h0a3.43 3.43 0 0 1-3.428-3.428v-2.228a3.43 3.43 0 0 1 3.428-3.428h0c1.271 0 2.381.692 2.973 1.72");
}

:global(.zj59rjbnw) {
  cx: 27.44px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

</style>
