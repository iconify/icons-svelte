<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="owyd6db1y"/><path class="cpzkqbbnc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:crop-duocolor" {...props}></Icon>
<style>
:global(.cpzkqbbnc) {
  d: path("M6 3v13a2 2 0 0 0 2 2h13M3 6h3m12 12v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.owyd6db1y) {
  stroke-opacity: 0.4;
  d: path("M10 6h6a2 2 0 0 1 2 2v6");
}

</style>
