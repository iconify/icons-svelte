<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mbt4yzbhr"/><path class="l065eyb2s"/><path class="vjmlnnb_l"/><path class="z9ittvbis"/><path class="vavi9cbgb"/><path class="k5g5kukae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:milestone-duotone-regular" {...props}></Icon>
<style>
:global(.k5g5kukae) {
  d: path("M8 7h10l-4 4 4 4H8");
}

:global(.l065eyb2s) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 7v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.mbt4yzbhr) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vavi9cbgb) {
  d: path("M8 7v12");
}

:global(.vjmlnnb_l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 7h10l-4 4 4 4H8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9ittvbis) {
  d: path("M2 19h20");
}

</style>
