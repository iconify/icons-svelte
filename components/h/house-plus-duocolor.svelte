<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mkz22f2th"/><path class="zh0cz3bnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-plus-duocolor" {...props}></Icon>
<style>
:global(.mkz22f2th) {
  stroke-opacity: 0.4;
  d: path("M9 14h6m-3-3v6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zh0cz3bnu) {
  d: path("m16 7l3 3c.64.64 1 1.36 1 2v7a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-7c0-.64.36-1.36 1-2l6-6a1.414 1.414 0 0 1 2 0z");
}

</style>
