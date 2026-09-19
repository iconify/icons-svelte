<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nrwk1wb-g"/><circle class="fin4upbaf"/><circle class="i9acr2sfe"/><circle class="f8esdpbuc"/><circle class="u6lm4_ikb"/><circle class="dkjxrwb8s"/><circle class="facg6hr-y"/><circle class="z85ba9bew"/><circle class="gexo91b7r"/><circle class="dto8lqbnf"/><circle class="ug0dkybnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fossify-keyboard" {...props}></Icon>
<style>
:global(.dkjxrwb8s) {
  cx: 36.989px;
  cy: 17.492px;
  r: 0.75px;
  fill: currentColor;
}

:global(.dto8lqbnf) {
  cx: 30.495px;
  cy: 23.97px;
  r: 0.75px;
  fill: currentColor;
}

:global(.f8esdpbuc) {
  cx: 24px;
  cy: 17.492px;
  r: 0.75px;
  fill: currentColor;
}

:global(.facg6hr-y) {
  cx: 11.011px;
  cy: 23.97px;
  r: 0.75px;
  fill: currentColor;
}

:global(.fin4upbaf) {
  cx: 11.011px;
  cy: 17.492px;
  r: 0.75px;
  fill: currentColor;
}

:global(.gexo91b7r) {
  cx: 24px;
  cy: 23.97px;
  r: 0.75px;
  fill: currentColor;
}

:global(.i9acr2sfe) {
  cx: 17.505px;
  cy: 17.492px;
  r: 0.75px;
  fill: currentColor;
}

:global(.nrwk1wb-g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.673 11.026h34.654A2.17 2.17 0 0 1 43.5 13.2v21.598a2.17 2.17 0 0 1-2.173 2.175H6.673A2.17 2.17 0 0 1 4.5 34.8V13.201a2.17 2.17 0 0 1 2.173-2.175m10.521 19.399h13.612");
}

:global(.u6lm4_ikb) {
  cx: 30.495px;
  cy: 17.492px;
  r: 0.75px;
  fill: currentColor;
}

:global(.ug0dkybnt) {
  cx: 36.989px;
  cy: 23.97px;
  r: 0.75px;
  fill: currentColor;
}

:global(.z85ba9bew) {
  cx: 17.505px;
  cy: 23.97px;
  r: 0.75px;
  fill: currentColor;
}

</style>
