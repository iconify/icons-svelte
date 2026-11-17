<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sodqk3r6m"/><path class="hy-_s9som"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:frying-pan-bulk" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hy-_s9som) {
  d: path("m14.553 10.106l6-3a1 1 0 1 1 .894 1.788l-6 3a1 1 0 1 1-.894-1.788");
}

:global(.sodqk3r6m) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 10a1 1 0 0 1 1 1v3a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3v-3a1 1 0 0 1 1-1Z");
}

</style>
