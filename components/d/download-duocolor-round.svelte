<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="skxyjccos"/><path class="tp9nqccpz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:download-duocolor-round" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.skxyjccos) {
  stroke-opacity: 0.4;
  d: path("M4 16a4 4 0 0 0 4 4h8a4 4 0 0 0 4-4");
}

:global(.tp9nqccpz) {
  d: path("m8 12l4 4l4-4m-4 4V4");
}

</style>
