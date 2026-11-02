<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="l9ycfeb_j"/><path class="p9nk_hb0c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-close-corner-duocolor-sharp" {...props}></Icon>
<style>
:global(.l9ycfeb_j) {
  stroke-opacity: 0.4;
  d: path("m14 14l6 6m0-6l-6 6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p9nk_hb0c) {
  d: path("M8 20H4V4h16v4");
}

</style>
