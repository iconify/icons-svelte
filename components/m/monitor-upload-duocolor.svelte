<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="j47yg1kmm"/><path class="oqu4abb4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-upload-duocolor" {...props}></Icon>
<style>
:global(.j47yg1kmm) {
  stroke-opacity: 0.4;
  d: path("m15 10l-3-3l-3 3m3-3v7");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oqu4abb4q) {
  d: path("M4 6a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v9a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm5 14h6");
}

</style>
