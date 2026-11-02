<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qgm4y23bk"/><path class="tw8j10bcb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layer-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.qgm4y23bk) {
  stroke-opacity: 0.4;
  d: path("m4 14l8 4l8-4");
}

:global(.tw8j10bcb) {
  d: path("m8 8l4-2l8 4l-8 4l-8-4z");
}

</style>
