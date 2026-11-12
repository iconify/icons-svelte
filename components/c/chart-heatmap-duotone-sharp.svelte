<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g8xfq7b5g"/><path class="cshn_qhcy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-heatmap-duotone-sharp" {...props}></Icon>
<style>
:global(.cshn_qhcy) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 3h18v18H3Zm9 0v18m-9-9h18M6 7a1 1 0 1 0 2 0a1 1 0 0 0-2 0m11 0h.01M16 17a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.g8xfq7b5g) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1");
}

</style>
