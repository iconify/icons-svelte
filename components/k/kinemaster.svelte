<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="o4he8abcm"/><circle class="tlkhku-6p"/><circle class="ow3zn9b5a"/><circle class="z38du568i"/><circle class="mb4g9zbzc"/><circle class="fmtxi7b7d"/><circle class="tlkhku-6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kinemaster" {...props}></Icon>
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

:global(.fmtxi7b7d) {
  cx: 6.881px;
  cy: 18.438px;
  r: 0.75px;
  fill: currentColor;
}

:global(.mb4g9zbzc) {
  cx: 13.42px;
  cy: 38.562px;
  r: 0.75px;
  fill: currentColor;
}

:global(.o4he8abcm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.374 13.533v20.934m11.252 0L20.991 24l8.635-10.467M20.991 24h-2.617");
}

:global(.ow3zn9b5a) {
  cx: 41.119px;
  cy: 18.438px;
  r: 0.75px;
  fill: currentColor;
}

:global(.tlkhku-6p) {
  cx: 24px;
  cy: 6px;
  r: 0.75px;
  fill: currentColor;
}

:global(.z38du568i) {
  cx: 34.58px;
  cy: 38.562px;
  r: 0.75px;
  fill: currentColor;
}

</style>
