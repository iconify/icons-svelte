<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nipabdbtb"/><path class="ueh98x_-c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folders-duocolor" {...props}></Icon>
<style>
:global(.nipabdbtb) {
  stroke-opacity: 0.4;
  d: path("M7 5a2 2 0 0 1 2-2h3l2 2m0 0h5a2 2 0 0 1 2 2v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ueh98x_-c) {
  d: path("M10 11h5a2 2 0 0 1 2 2v6a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2v-8a2 2 0 0 1 2-2h3z");
}

</style>
