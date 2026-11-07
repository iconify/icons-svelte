<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="axcf-wb4p"/><path class="b-1gkojdj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chat-circle-off-duocolor" {...props}></Icon>
<style>
:global(.axcf-wb4p) {
  stroke-opacity: 0.4;
  d: path("m2 2l20 20");
}

:global(.b-1gkojdj) {
  d: path("m18 19l-2 1a8.94 8.94 0 0 1-8 0l-5 1l1-5a8.94 8.94 0 0 1 0-8l1-2m5-3a9.22 9.22 0 0 1 11 11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
