<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="c4hipffst"/><circle class="sqh8d-abj"/><circle class="wkcz4_l2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alertus" {...props}></Icon>
<style>
:global(.c4hipffst) {
  cx: 21.098px;
  cy: 26.902px;
  r: 17.365px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sqh8d-abj) {
  cx: 18.533px;
  cy: 29.467px;
  r: 13.879px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.wkcz4_l2z) {
  cx: 16.259px;
  cy: 31.741px;
  r: 10.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
