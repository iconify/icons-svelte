<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ww1io6bum"/><path class="gxesbv2vg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:library-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gxesbv2vg) {
  d: path("M9 3v18a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0");
}

:global(.ww1io6bum) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 5a3 3 0 0 1 3-3h4c1.188 0 2.263.697 2.743 1.784l3.014-.754a1 1 0 0 1 1.213.727l4 16a1 1 0 0 1-.727 1.213l-4 1a1 1 0 0 1-1.213-.727L13 13.123V19a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

</style>
