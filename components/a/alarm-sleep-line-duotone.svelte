<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="nd-3gubon"/><path class="x43s2zn6y"/><path class="pfllnjb4h"/><path class="dul6eto5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-sleep-line-duotone" {...props}></Icon>
<style>
:global(.dul6eto5z) {
  stroke-linejoin: round;
  d: path("M9 10H15L9 16H15");
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nd-3gubon) {
  cx: 12px;
  cy: 13px;
  r: 9px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.pfllnjb4h) {
  stroke-linejoin: round;
  d: path("M20.5 4.5L16.5 2");
}

:global(.x43s2zn6y) {
  stroke-linejoin: round;
  d: path("M3.5 4.5L7.50002 2");
}

</style>
