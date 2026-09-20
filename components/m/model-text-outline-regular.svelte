<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p39ktbcba"/><path class="xrit8bb9e"/><path class="ltxni2ncy"/><path class="vg0qlegui"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-text-outline-regular" {...props}></Icon>
<style>
:global(.ltxni2ncy) {
  d: path("M14 12h7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p39ktbcba) {
  d: path("m7 8 4 4 -4 4 -4 -4Z");
}

:global(.vg0qlegui) {
  d: path("M14 17h7");
}

:global(.xrit8bb9e) {
  d: path("M14 7h7");
}

</style>
