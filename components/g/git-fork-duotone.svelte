<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s6ikctwul"/><path class="eyh4va5au"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:git-fork-duotone" {...props}></Icon>
<style>
:global(.eyh4va5au) {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m14 0a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-7 12a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2-6v4M5 8v2a2 2 0 0 0 2 2h10a2 2 0 0 0 2-2V8");
}

:global(.ft5dv1b6b) {
  fill: none;
}

:global(.s6ikctwul) {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 6a2 2 0 1 1 3.999-.001A2 2 0 0 1 3 6m14 0a2 2 0 1 1 3.999-.001A2 2 0 0 1 17 6m-7 12a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 18");
}

</style>
