<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yp3mgkoam"/><path class="dqguevbeq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:ethernet-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dqguevbeq) {
  d: path("M7 8v3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4 0v3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m4 3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0Zm4-3v3a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0");
}

:global(.yp3mgkoam) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 18a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v9a3 3 0 0 1-3 3h-1v2a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2v-2Z");
}

</style>
