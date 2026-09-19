<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o707_xbjc"/><ellipse class="j1-76lb_p"/><circle class="a6r9ykbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dndrulebook" {...props}></Icon>
<style>
:global(.a6r9ykbin) {
  cx: 26.17px;
  cy: 24px;
  r: 4.18px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.j1-76lb_p) {
  cx: 26.16px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 9px;
  ry: 4.18px;
}

:global(.o707_xbjc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.5v35a2 2 0 0 0 2 2h2.33v-39H10.4a2 2 0 0 0-2 2m4.33-2v39H37.6a2 2 0 0 0 2-2v-35a2 2 0 0 0-2-2Z");
}

</style>
