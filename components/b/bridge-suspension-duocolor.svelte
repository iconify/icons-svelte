<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d6ixxrb7o"/><path class="osfad-bid"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bridge-suspension-duocolor" {...props}></Icon>
<style>
:global(.d6ixxrb7o) {
  stroke-opacity: 0.4;
  d: path("M6 6a6.325 6.325 0 0 0 12 0m-6 5v4M3 9l3-3m12 0l3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.osfad-bid) {
  d: path("M3 15h18M6 3v16M18 3v16");
}

</style>
