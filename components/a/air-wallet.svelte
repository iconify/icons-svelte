<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="jvlfg9bui"/><path class="sirpbtoqy"/><circle class="n-3d6ac_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:air-wallet" {...props}></Icon>
<style>
:global(.jvlfg9bui) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.5px;
  ry: 5.5px;
}

:global(.n-3d6ac_a) {
  cx: 35px;
  cy: 29.5px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sirpbtoqy) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 22c0-3.047-2.453-5.5-5.5-5.5H11A5.49 5.49 0 0 1 5.5 11");
}

</style>
