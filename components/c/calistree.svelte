<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="kn3v_bj-u"/><circle class="h7_r23o4y"/><circle class="ss2rf3fnw"/><path class="tc4wk_bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:calistree" {...props}></Icon>
<style>
:global(.h7_r23o4y) {
  cx: 13px;
  cy: 20px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.kn3v_bj-u) {
  cx: 24px;
  cy: 38px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ss2rf3fnw) {
  cx: 35.5px;
  cy: 8.5px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tc4wk_bzt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 20c3.544 0 6.5.5 6.5 6.5m7.5-18C25.108 8.5 24 12.916 24 20v12.5");
}

</style>
