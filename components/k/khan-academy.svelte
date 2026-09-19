<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vrs1ps4fi"/><circle class="lt2p51b5j"/><path class="lv2qjab1s"/><path class="pmzws97px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:khan-academy" {...props}></Icon>
<style>
:global(.lt2p51b5j) {
  cx: 24.031px;
  cy: 16.866px;
  r: 3.689px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lv2qjab1s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.754 20.98a13.703 13.703 0 1 1-27.301 0");
}

:global(.pmzws97px) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.453 20.98A13.703 13.703 0 0 1 24.18 34.681m.11-.001a13.703 13.703 0 0 1 13.464-13.7");
}

:global(.vrs1ps4fi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.017 43.5L7.03 33.764l-.017-19.5L23.982 4.5l16.989 9.736l.017 19.5Z");
}

</style>
