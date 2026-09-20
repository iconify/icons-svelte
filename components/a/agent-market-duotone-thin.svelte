<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o9ks72bnu"/><path class="a85y0t8_i"/><path class="skbifdbcx"/><path class="i3qzahbyw"/><path class="wtfq6b2ta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-market-duotone-thin" {...props}></Icon>
<style>
:global(.a85y0t8_i) {
  fill: currentColor;
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.i3qzahbyw) {
  d: path("M11 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

:global(.o9ks72bnu) {
  fill: currentColor;
  d: path("M11 16a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.skbifdbcx) {
  d: path("M8.69 3.37a4 4 0 1 1 -3.38 0");
}

:global(.wtfq6b2ta) {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
