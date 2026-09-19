<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="v8cxm8n7m"/><circle class="u7ye2infl"/><circle class="lrz7s9hqw"/><circle class="i9eoxlbhx"/><circle class="q5ay8ln6e"/><circle class="xbv2nbclp"/><circle class="txxib_npc"/><circle class="g5ft-tbjd"/><path class="ctn5ocbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dots-and-co" {...props}></Icon>
<style>
:global(.ctn5ocbki) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.134 19.5l-4.619 8a1 1 0 0 0 .866 1.5h9.238a1 1 0 0 0 .866-1.5l-4.619-8a1 1 0 0 0-1.732 0");
}

:global(.g5ft-tbjd) {
  cx: 24px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.i9eoxlbhx) {
  cx: 10px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.lrz7s9hqw) {
  cx: 24px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.q5ay8ln6e) {
  cx: 38px;
  cy: 24px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.txxib_npc) {
  cx: 38px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.u7ye2infl) {
  cx: 38px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.v8cxm8n7m) {
  cx: 10px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xbv2nbclp) {
  cx: 10px;
  cy: 38px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
