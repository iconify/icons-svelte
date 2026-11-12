<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="o_7-63buy"/><path class="jqyqz0bst"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:chart-bar-stacked-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.jqyqz0bst) {
  d: path("M14 14v-1h-4v7a1 1 0 0 1-2 0v-4H3a1 1 0 0 1 0-2h5v-3a1 1 0 0 1 2 0h4V8a1 1 0 0 1 2 0v5h5a1 1 0 0 1 0 2h-5v5a1 1 0 0 1-2 0Z");
}

:global(.o_7-63buy) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10 3h4a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m7 4h4a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1M3 10h4a1 1 0 0 1 1 1v9a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-9a1 1 0 0 1 1-1");
}

</style>
