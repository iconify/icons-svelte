<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="sfwc6oboi"/><path class="hy-_s9som"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:frying-pan-bulk-sharp" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hy-_s9som) {
  d: path("m14.553 10.106l6-3a1 1 0 1 1 .894 1.788l-6 3a1 1 0 1 1-.894-1.788");
}

:global(.sfwc6oboi) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10h12a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1");
}

</style>
