<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xkmyahbnq"/><path class="ll0g54h-q"/><circle class="th6p4xhwr"/><circle class="iyv21xbwf"/><circle class="n1hwhu0gl"/><circle class="g2ly9ubtg"/><path class="xe80qevbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:countries-been" {...props}></Icon>
<style>
:global(.g2ly9ubtg) {
  cx: 21.306px;
  cy: 35.575px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.iyv21xbwf) {
  cx: 37.582px;
  cy: 15.922px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.ll0g54h-q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

:global(.n1hwhu0gl) {
  cx: 15.752px;
  cy: 23.412px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.th6p4xhwr) {
  cx: 25.268px;
  cy: 11.037px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.xe80qevbd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.306 35.575h6.778M18.301 24.989L24 28.514m2.602-14.8l2.2 4.416m9.371.792l.986 5");
}

:global(.xkmyahbnq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.612 15.498C23.095 19.29 14.659 29.868 14.037 42.5M42.5 14.037q-1.226.06-2.425.217");
}

</style>
