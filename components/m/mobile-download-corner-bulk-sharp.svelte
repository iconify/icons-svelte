<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c70wyxjpe"/><path class="ctynhw5wp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mobile-download-corner-bulk-sharp" {...props}></Icon>
<style>
:global(.c70wyxjpe) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 2h10a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-2v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1");
}

:global(.ctynhw5wp) {
  d: path("m16.293 21.707l-3-3a1 1 0 0 1 1.414-1.414L16 18.586V13a1 1 0 0 1 2 0v5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414l-3 3a1 1 0 0 1-1.414 0");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

</style>
