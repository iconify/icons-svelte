<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zds7z8bri"/><path class="iujogacxf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:charging-station-duocolor-round" {...props}></Icon>
<style>
:global(.iujogacxf) {
  d: path("M3 7a4 4 0 0 1 4-4h2a4 4 0 0 1 4 4v10a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4Zm10 5h2a2 2 0 0 1 2 2v1a2 2 0 1 0 4 0V8c0-.64-.36-1.36-1-2l-2-2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zds7z8bri) {
  stroke-opacity: 0.4;
  d: path("m9 8l-3 4h4l-3 4");
}

</style>
