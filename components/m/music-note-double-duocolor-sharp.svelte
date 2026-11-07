<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxlq3mw-f"/><path class="x-le5iiml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-double-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x-le5iiml) {
  d: path("M6 17a3 3 0 1 0 6 0a3 3 0 0 0-6 0m6 0V4l6 3");
}

:global(.xxlq3mw-f) {
  stroke-opacity: 0.4;
  d: path("m12 9l4 2");
}

</style>
