<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ycx5d_b4j"/><path class="ex6sma95g"/><path class="c2-gs7b7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:crypto-coin-duotone-regular" {...props}></Icon>
<style>
:global(.c2-gs7b7d) {
  d: path("m15 9 -3 3h2.5l-3 3");
}

:global(.ex6sma95g) {
  d: path("M8 3h8l5 5v8l-5 5H8l-5 -5V8Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ycx5d_b4j) {
  fill: currentColor;
  d: path("M8 3h8l5 5v8l-5 5H8l-5 -5V8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
