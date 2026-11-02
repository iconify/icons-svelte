<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ra34vcrze"/><path class="nq9fwlbqy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-2-duocolor" {...props}></Icon>
<style>
:global(.nq9fwlbqy) {
  d: path("M3 20h18M5 20v-8c0-.64.36-1.36 1-2l5-5a1.414 1.414 0 0 1 2 0l5 5c.64.64 1 1.36 1 2v8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ra34vcrze) {
  stroke-opacity: 0.4;
  d: path("M10 20v-4a2 2 0 1 1 4 0v4");
}

</style>
