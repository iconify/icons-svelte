<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cwp5bj8es"/><path class="xsfy-2b7l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:graphics-card-duocolor-sharp" {...props}></Icon>
<style>
:global(.cwp5bj8es) {
  stroke-opacity: 0.4;
  d: path("M6 11a2 2 0 1 0 4 0a2 2 0 0 0-4 0m8 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xsfy-2b7l) {
  d: path("M3 5h18v12H3Zm0-2v18m4-4v4h10v-4");
}

</style>
