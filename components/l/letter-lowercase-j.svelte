<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="vtsuf-pip"/><circle class="w-6ipp0zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:letter-lowercase-j" {...props}></Icon>
<style>
:global(.j3s9ivbxi) {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

:global(.vtsuf-pip) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.007 18.275v12c0 2.21-1.774 4-3.962 4a3.93 3.93 0 0 1-2.802-1.172");
}

:global(.w-6ipp0zu) {
  cx: 27.007px;
  cy: 14.475px;
  r: 0.75px;
  fill: currentColor;
}

</style>
