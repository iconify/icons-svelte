<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ma1kg5nak"/><path class="id4-i3bwx"/><path class="t3y19xb5z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bicycle" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.id4-i3bwx) {
  d: path("M5.5 15.5H12l4-6l2.5 6");
}

:global(.ma1kg5nak) {
  d: path("M2 15.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0m13 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0");
}

:global(.t3y19xb5z) {
  d: path("m5.5 15.5l5-6H16m-4 6l-2-8m-1.5 0h3m4.5 2L15 7h2.5");
}

</style>
