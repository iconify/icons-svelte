<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t0xm9xv2t"/><path class="v23z8imjm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:layer-bulk-round" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.t0xm9xv2t) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m7.553 7.106l4-2a1 1 0 0 1 .894 0l6 3a2.116 2.116 0 0 1 0 3.788l-6 3a1 1 0 0 1-.894 0l-6-3a2.116 2.116 0 0 1 0-3.788Z");
}

:global(.v23z8imjm) {
  d: path("m12 16.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788Z");
}

</style>
