<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="u0ziftu8f"/><path class="kr65-pbjz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:pencil-ruler-duocolor-round" {...props}></Icon>
<style>
:global(.kr65-pbjz) {
  d: path("M4 16L14 6a2.828 2.828 0 1 1 4 4L8 20m0 0H4v-4m7-11L9 7m10 6l-2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.u0ziftu8f) {
  stroke-opacity: 0.4;
  d: path("m13 7l-2-2a2.83 2.83 0 0 0-4 0L5 7a2.83 2.83 0 0 0 0 4l2 2m10-2l2 2a2.83 2.83 0 0 1 0 4l-2 2a2.83 2.83 0 0 1-4 0l-2-2");
}

</style>
