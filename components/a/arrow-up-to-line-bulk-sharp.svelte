<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="suz3f6b8m"/><path class="khay96b3w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:arrow-up-to-line-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.khay96b3w) {
  d: path("M13 10.414V20a1 1 0 0 1-2 0v-9.586l-2.293 2.293a.999.999 0 1 1-1.414-1.414l4-4a.997.997 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Z");
}

:global(.suz3f6b8m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 3h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

</style>
