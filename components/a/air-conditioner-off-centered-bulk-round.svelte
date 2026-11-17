<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nchg0thkb"/><path class="aakag8i1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:air-conditioner-off-centered-bulk-round" {...props}></Icon>
<style>
:global(.aakag8i1b) {
  d: path("M7 12h10a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nchg0thkb) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 7h10a5 5 0 0 1 0 10H7A5 5 0 0 1 7 7");
}

</style>
