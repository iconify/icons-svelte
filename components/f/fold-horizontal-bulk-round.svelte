<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qxhez1b1m"/><path class="htnt4uysm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:fold-horizontal-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.htnt4uysm) {
  d: path("M7.586 13H3a1 1 0 0 1 0-2h4.586L6.293 9.707a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414Zm8.828-2H21a1 1 0 0 1 0 2h-4.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414Z");
}

:global(.qxhez1b1m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 8a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0Zm0 12a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Z");
}

</style>
