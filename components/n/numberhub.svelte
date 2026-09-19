<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="n0s9_cb_u"/><path class="zquni4omk"/><circle class="o_-_f9jda"/><path class="v2yll8ses"/><circle class="lg_2l3b-d"/><circle class="zwrsq9apw"/><circle class="iotnjkb8f"/><path class="r28s358rq"/><circle class="jexvsdggb"/><path class="ly4m8msvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:numberhub" {...props}></Icon>
<style>
:global(.iotnjkb8f) {
  cx: 34.547px;
  cy: 30px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jexvsdggb) {
  cx: 14.5px;
  cy: 33.5px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lg_2l3b-d) {
  cx: 34.5px;
  cy: 33.5px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ly4m8msvk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.318 30.318l6.364 6.364m0-6.364l-6.364 6.364");
}

:global(.n0s9_cb_u) {
  cx: 14.5px;
  cy: 13.5px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.o_-_f9jda) {
  cx: 34.5px;
  cy: 13.5px;
  r: 8.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.r28s358rq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.047 33.5h9");
}

:global(.v2yll8ses) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.047 13.5h9");
}

:global(.zquni4omk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10 13.5h9M14.5 9v9");
}

:global(.zwrsq9apw) {
  cx: 34.547px;
  cy: 37px;
  r: 1.25px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
