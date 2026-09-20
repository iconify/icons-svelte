<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cw_3-ccnb"/><path class="h8b2rkgcl"/><path class="cu5fjhbmy"/><path class="qii79lbir"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:flashcard-duotone-regular" {...props}></Icon>
<style>
:global(.cu5fjhbmy) {
  d: path("M16 6v5h5");
}

:global(.cw_3-ccnb) {
  fill: currentColor;
  d: path("M3 6h13l5 5v7H3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.h8b2rkgcl) {
  d: path("M3 6h13l5 5v7H3Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qii79lbir) {
  d: path("M6 14h8");
}

</style>
