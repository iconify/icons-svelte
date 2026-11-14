<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a1n-y6b0f"/><path class="s1thihbdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cinema-exit-sign" {...props}></Icon>
<style>
:global(.a1n-y6b0f) {
  d: path("M6 6h12a3.5 3.5 0 0 1 3.5 3.5v5A3.5 3.5 0 0 1 18 18H6a3.5 3.5 0 0 1-3.5-3.5v-5A3.5 3.5 0 0 1 6 6m1 6h9.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1thihbdu) {
  d: path("M13.25 8.75L16.5 12l-3.25 3.25");
}

</style>
