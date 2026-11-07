<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxlq3mw-f"/><path class="c-szcib2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-double-duocolor" {...props}></Icon>
<style>
:global(.c-szcib2v) {
  d: path("M6 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 0V6c0-.919 1.081-1.46 2-1l4 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xxlq3mw-f) {
  stroke-opacity: 0.4;
  d: path("m12 9l4 2");
}

</style>
