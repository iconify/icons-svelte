<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t8ldchbht"/><path class="zovgs7byh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:network-off-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.t8ldchbht) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.243 2H15a1 1 0 0 1 1 1v5c0 .206-.064.407-.182.575ZM3 15h6a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1m15 0l4 4v2a1 1 0 0 1-1 1h-6a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Z");
}

:global(.zovgs7byh) {
  d: path("m5.707 1.293l17 17a.999.999 0 1 1-1.414 1.414L14.586 13H7v3a1 1 0 0 1-2 0v-4a1 1 0 0 1 1-1h6.586L4.293 2.707a.999.999 0 1 1 1.414-1.414");
}

</style>
