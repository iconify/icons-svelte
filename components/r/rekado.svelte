<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="p90tk8ihw"/><circle class="sftzhvb2s"/><circle class="k60inxbjs"/><path class="zi3ccu_jq"/><circle class="k2g_rubtw"/><circle class="frlygtb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:rekado" {...props}></Icon>
<style>
:global(.frlygtb3a) {
  cx: 28.258px;
  cy: 22.765px;
  r: 1.403px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k2g_rubtw) {
  cx: 20.715px;
  cy: 29.984px;
  r: 2.752px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.k60inxbjs) {
  cx: 32.817px;
  cy: 22.765px;
  r: 1.403px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.p90tk8ihw) {
  cx: 28.258px;
  cy: 18.205px;
  r: 1.403px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.sftzhvb2s) {
  cx: 32.817px;
  cy: 18.205px;
  r: 1.403px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.zi3ccu_jq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.495 5.5L5.88 33.367l6.416 6.616c2.967 3.425 8.483 3.287 12.204 0l15.46-15.888c2.171-2.05 3.36-8.056.35-11.428Z");
}

</style>
