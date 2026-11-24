<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wb0mm3bek"/><path class="n3ytvnb7z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:lock-duocolor" {...props}></Icon>
<style>
:global(.n3ytvnb7z) {
  d: path("M4 11a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2Zm7 4a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wb0mm3bek) {
  stroke-opacity: 0.4;
  d: path("M8 9V7a4 4 0 1 1 8 0v2");
}

</style>
