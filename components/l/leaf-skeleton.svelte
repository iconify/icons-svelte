<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e7v5b6dnm"/><path class="mgj8bra_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:leaf-skeleton" {...props}></Icon>
<style>
:global(.e7v5b6dnm) {
  d: path("M5.25 18.75c0-9.5 5.5-15 15-15c0 9.5-5.5 15-15 15m-1.5 1.5l1.5-1.5m0 0L17.5 6.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mgj8bra_x) {
  d: path("m6.25 12.5l1.25 4l4 1.25m-2.25-10L11 13l5.25 1.75m-2.5-10l.75 4.75l4.75.75");
}

</style>
