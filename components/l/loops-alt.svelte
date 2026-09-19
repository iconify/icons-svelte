<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="xsqzccc6b"/><path class="gcewahbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:loops-alt" {...props}></Icon>
<style>
:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gcewahbir) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.5 24h5M15.75 38.289l-2.5 4.33m2.5-32.909l-2.5-4.33m7.574 13.12a1.5 1.5 0 0 0-.75 1.299V28.2a1.5 1.5 0 0 0 2.25 1.299l7.277-4.201a1.5 1.5 0 0 0 0-2.598l-7.277-4.2a1.5 1.5 0 0 0-1.5 0");
}

:global(.xsqzccc6b) {
  cx: 24px;
  cy: 24px;
  r: 16.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
