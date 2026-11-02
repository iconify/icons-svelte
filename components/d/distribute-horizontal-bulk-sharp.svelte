<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rx8dbcn9j"/><path class="yu2y7hbmc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:distribute-horizontal-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.rx8dbcn9j) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1Z");
}

:global(.yu2y7hbmc) {
  d: path("M5 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0m16 0v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

</style>
