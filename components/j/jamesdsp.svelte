<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="a3oit5blr"/><circle class="mvfv9aceq"/><path class="oegv-2u8r"/><circle class="jrsxdff1m"/><path class="rdxtyfl2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:jamesdsp" {...props}></Icon>
<style>
:global(.a3oit5blr) {
  cx: 8.14px;
  cy: 16.11px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jrsxdff1m) {
  cx: 24px;
  cy: 31.89px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.mvfv9aceq) {
  cx: 39.86px;
  cy: 16.11px;
  r: 3.64px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.oegv-2u8r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.14 12.47V8.4m0 11.35V39.6m31.72-27.13V8.4m0 11.35V39.6");
}

:global(.rdxtyfl2r) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 35.53v4.07m0-11.35V8.4");
}

</style>
