<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ur7lewiwv"/><path class="ucpw8ullu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:house-alt-4-duocolor" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.ucpw8ullu) {
  d: path("m3 11l7.671-6.819a2 2 0 0 1 2.658 0L21 11m-2-1.778V19a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V9.222");
}

:global(.ur7lewiwv) {
  stroke-opacity: 0.4;
  d: path("M12 17h-2a1 1 0 0 1-1-1v-3.884a1 1 0 0 1 .336-.748l2-1.777a1 1 0 0 1 1.328 0l2 1.777a1 1 0 0 1 .336.748V16a1 1 0 0 1-1 1z");
}

</style>
