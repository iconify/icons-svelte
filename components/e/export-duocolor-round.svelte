<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iyqeu-beg"/><path class="x9vys6b8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:export-duocolor-round" {...props}></Icon>
<style>
:global(.iyqeu-beg) {
  stroke-opacity: 0.4;
  d: path("m15 6l-3-3l-3 3m3-3v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x9vys6b8c) {
  d: path("M5 7a2 2 0 0 0-2 2v8a4 4 0 0 0 4 4h10a4 4 0 0 0 4-4V9a2 2 0 0 0-2-2");
}

</style>
