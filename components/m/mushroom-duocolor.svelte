<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hiyfnwbgc"/><path class="w-mn8bmrv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mushroom-duocolor" {...props}></Icon>
<style>
:global(.hiyfnwbgc) {
  stroke-opacity: 0.4;
  d: path("M10 11v8a2 2 0 1 0 4 0v-8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.w-mn8bmrv) {
  d: path("M4 11a8 8 0 1 1 16 0Z");
}

</style>
