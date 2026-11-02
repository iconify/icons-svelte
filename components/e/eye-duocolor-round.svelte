<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eu2qvtbww"/><path class="i7-vc1bal"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:eye-duocolor-round" {...props}></Icon>
<style>
:global(.eu2qvtbww) {
  stroke-opacity: 0.4;
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.i7-vc1bal) {
  d: path("M3 12a9.75 9.75 0 0 1 18 0a9.75 9.75 0 0 1-18 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
