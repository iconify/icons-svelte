<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uudyrgb2a"/><path class="ko7vgklqj"/><path class="rki_rg93o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funicular-outline-regular" {...props}></Icon>
<style>
:global(.ko7vgklqj) {
  d: path("m4 20 4 -4h6l-4 4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.rki_rg93o) {
  d: path("m12 12 4 -4h6l-4 4Z");
}

:global(.uudyrgb2a) {
  d: path("M2 21 21 2");
}

</style>
