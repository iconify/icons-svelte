<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r2ln9-bjf"/><path class="qlhwh_brj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:building-4-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qlhwh_brj) {
  d: path("M3 20h18M5 20V6a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v14m0-11h2a2 2 0 0 1 2 2v9");
}

:global(.r2ln9-bjf) {
  stroke-opacity: 0.4;
  d: path("M9 8h2m-2 4h2");
}

</style>
