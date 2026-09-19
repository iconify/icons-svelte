<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="hfqsv-8db"/><circle class="j0xu6tunt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hollandsnieuwe" {...props}></Icon>
<style>
:global(.hfqsv-8db) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.999 15.588v14.266M13 23.97a3.567 3.567 0 0 1 3.566-3.567h0a3.567 3.567 0 0 1 3.567 3.566v5.885m10.867 0V23.97a3.567 3.567 0 0 0-3.567-3.567h0a3.567 3.567 0 0 0-3.567 3.567m0 5.884v-9.452");
}

:global(.j0xu6tunt) {
  cx: 34.251px;
  cy: 29.663px;
  r: 0.75px;
  fill: currentColor;
}

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

</style>
