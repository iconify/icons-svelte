<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vofc4_bbb"/><path class="onffe2clz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:headphones-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.onffe2clz) {
  d: path("M4.629 8.886A8.002 8.002 0 0 1 20 12a1 1 0 0 1-2 0a6 6 0 1 0-12 0a1 1 0 0 1-2 0a7.9 7.9 0 0 1 .629-3.114");
}

:global(.vofc4_bbb) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 11h5a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1m13 0h5a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1");
}

</style>
