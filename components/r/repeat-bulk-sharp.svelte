<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ggx0oswmo"/><path class="fog19whkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:repeat-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.fog19whkb) {
  d: path("M18.586 7H4v4a1 1 0 0 1-2 0V6a1 1 0 0 1 1-1h15.586l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414ZM22 18a1 1 0 0 1-1 1H5.414l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414L5.414 17H20v-4a1 1 0 0 1 2 0Z");
}

:global(.ggx0oswmo) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 6h18v12H3Z");
}

</style>
