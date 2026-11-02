<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="panz28b2u"/><path class="pq0g_s25h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-branch-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.panz28b2u) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m14 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0M2 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

:global(.pq0g_s25h) {
  d: path("M6 8v3.171A3 3 0 0 1 7 11h10a1 1 0 0 0 1-1V8a1 1 0 0 1 2 0v2a3 3 0 0 1-3 3H6.998A1 1 0 0 0 6 14v2a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0");
}

</style>
