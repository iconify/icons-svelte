<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qsjc4stbt"/><path class="ltupbjb0d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:candle-chart-duotone-regular" {...props}></Icon>
<style>
:global(.ltupbjb0d) {
  d: path("M5 10.5V13m-2 0h4v5H3Zm2 5v2.5m7 -14V9m-2 0h4v5h-4Zm2 5v2.5m7 -14V5m-2 0h4v5h-4Zm2 5v2.5");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qsjc4stbt) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 10.5V13m-2 0h4v5H3Zm2 5v2.5m7 -14V9m-2 0h4v5h-4Zm2 5v2.5m7 -14V5m-2 0h4v5h-4Zm2 5v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
