<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zw6gp5s_j"/><path class="q_a5zcbnk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:circle-currency-bitcoin-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q_a5zcbnk) {
  d: path("M3 12a9 9 0 1 0 18 0a9 9 0 0 0-18 0");
}

:global(.zw6gp5s_j) {
  stroke-opacity: 0.4;
  d: path("M9 7v10m0-9h3a2 2 0 1 1 0 4H9m0 0h4a2 2 0 1 1 0 4H9m4-9v1m0 8v1");
}

</style>
