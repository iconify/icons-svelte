<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rufoxdbmp"/><path class="jd15n1qhh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:brick-wall-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jd15n1qhh) {
  d: path("M13 7h8a1 1 0 0 1 0 2h-4v2h4a1 1 0 0 1 0 2h-8v2h8a1 1 0 0 1 0 2h-4v3a1 1 0 0 1-2 0v-3H9v3a1 1 0 0 1-2 0v-3H3a1 1 0 0 1 0-2h8v-2H3a1 1 0 0 1 0-2h4V9H3a1 1 0 0 1 0-2h8V4a1 1 0 0 1 2 0Zm-1 2H9v2h6V9Z");
}

:global(.rufoxdbmp) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 3h18a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1");
}

</style>
