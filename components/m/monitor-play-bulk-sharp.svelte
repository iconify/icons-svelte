<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sq2a32-oo"/><path class="d933zlbav"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:monitor-play-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d933zlbav) {
  d: path("m10.573 6.181l5 3.5a1 1 0 0 1 0 1.638l-5 3.5A1 1 0 0 1 9 14V7a.999.999 0 0 1 1.573-.819M11 12.079l2.256-1.579L11 8.921ZM9 19h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

:global(.sq2a32-oo) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v13a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
