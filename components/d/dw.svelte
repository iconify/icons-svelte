<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gy4owibag"/><circle class="r3ft9ub_i"/><path class="s7rarnbkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:dw" {...props}></Icon>
<style>
:global(.gy4owibag) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.897 29.016V18.984h2.257a4.39 4.39 0 0 1 4.39 4.389v1.254a4.39 4.39 0 0 1-4.39 4.39Zm25.014-10.032l-2.508 10.032l-2.508-10.032l-2.508 10.032l-2.508-10.032");
}

:global(.r3ft9ub_i) {
  cx: 15.105px;
  cy: 24px;
  r: 11.605px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s7rarnbkd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.999 16.547a11.605 11.605 0 1 1 0 14.906");
}

</style>
