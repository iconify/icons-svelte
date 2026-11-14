<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="up54bibqb"/><path class="pyzluwbgv"/><path class="nr2kwkbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:crypto-chart" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.nr2kwkbiv) {
  d: path("M17 15h2a3 3 0 0 1 0 6h-2");
}

:global(.pyzluwbgv) {
  d: path("m7 15.5l4-4.5l2.673 2.227m1.021-.547L19.5 7M14 18a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

:global(.up54bibqb) {
  d: path("M3.5 3.5v17h8.3");
}

</style>
