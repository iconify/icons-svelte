<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="la93r9bqf"/><circle class="s7tba086c"/><circle class="uxtwmwvld"/><path class="smmmhxg8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:crayon" {...props}></Icon>
<style>
:global(.la93r9bqf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.24 44.338V14.902A11.273 11.273 0 0 0 24 3.662h0a11.273 11.273 0 0 0-11.24 11.24v29.374Z");
}

:global(.s7tba086c) {
  cx: 19.611px;
  cy: 15.13px;
  r: 1.967px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

:global(.smmmhxg8d) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M26.49 20.166a.78.78 0 0 1 .708 1.113a3.581 3.581 0 0 1-6.398-.001a.78.78 0 0 1 .709-1.112Z");
}

:global(.uxtwmwvld) {
  cx: 28.389px;
  cy: 15.13px;
  r: 1.967px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

</style>
