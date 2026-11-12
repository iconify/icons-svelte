<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="djxxm2q5p"/><path class="n5iafhovj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-angry-duocolor-round" {...props}></Icon>
<style>
:global(.djxxm2q5p) {
  stroke-opacity: 0.4;
  d: path("m8 9l2 1m6-1l-2 1m-6 5a5.657 5.657 0 0 1 8 0");
}

:global(.n5iafhovj) {
  d: path("M4 16a8.944 8.944 0 1 1 4 4l-5 1Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
