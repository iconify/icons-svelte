<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x1iwzp61z"/><path class="gzypby2pf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:popover-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.gzypby2pf) {
  d: path("M7 11h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2m0 4h6a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

:global(.x1iwzp61z) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 6a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5v-6a5 5 0 0 1 5-5h1.5l2.7-3.6a1 1 0 0 1 1.6 0L15.5 6Z");
}

</style>
