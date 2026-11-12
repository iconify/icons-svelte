<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w5c7hhbzp"/><path class="je8wj4_2v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:magnet-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.je8wj4_2v) {
  d: path("M8 7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm13 0a1 1 0 0 1 0 2h-5a1 1 0 0 1 0-2Z");
}

:global(.w5c7hhbzp) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v7a3 3 0 1 0 6 0V5a3 3 0 0 1 3-3h1a3 3 0 0 1 3 3v7c0 5.523-4.477 10-10 10S2 17.523 2 12Z");
}

</style>
