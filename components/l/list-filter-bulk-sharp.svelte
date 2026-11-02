<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w64nktv8n"/><path class="mhfhcxrih"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-filter-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.mhfhcxrih) {
  d: path("M4 5h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

:global(.w64nktv8n) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 11a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2Zm-3 6a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Z");
}

</style>
