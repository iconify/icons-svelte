<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d223d_x9q"/><path class="uhawluh-v"/><path class="cpmzr29ux"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:encoder-only-outline-regular" {...props}></Icon>
<style>
:global(.cpmzr29ux) {
  d: path("m16 8 4 4 -4 4 -4 -4Z");
}

:global(.d223d_x9q) {
  d: path("M3 12h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uhawluh-v) {
  d: path("M6.5 9.5 9 12l-2.5 2.5");
}

</style>
