<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hlbz2lbqc"/><path class="t0r-1-bvp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:currency-ethereum-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.hlbz2lbqc) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.832 2.445l6 9a1 1 0 0 1 0 1.11l-6 9a1 1 0 0 1-1.664 0l-6-9a1 1 0 0 1 0-1.11l6-9a1 1 0 0 1 1.664 0");
}

:global(.t0r-1-bvp) {
  d: path("m12 13.882l5.553-2.776a1 1 0 1 1 .894 1.788l-6 3a1 1 0 0 1-.894 0l-6-3a1 1 0 1 1 .894-1.788Z");
}

</style>
