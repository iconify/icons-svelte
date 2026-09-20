<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="uudyrgb2a"/><path class="ko7vgklqj"/><path class="rki_rg93o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:funicular-outline-bold" {...props}></Icon>
<style>
:global(.ko7vgklqj) {
  d: path("m4 20 4 -4h6l-4 4Z");
}

:global(.rki_rg93o) {
  d: path("m12 12 4 -4h6l-4 4Z");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.uudyrgb2a) {
  d: path("M2 21 21 2");
}

</style>
