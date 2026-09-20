<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="l2zed5t1y"/><path class="qcsst5bvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:pint-glass-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.l2zed5t1y) {
  d: path("m195.2 72l-18.35 153a8 8 0 0 1-7.95 7H87.1a8 8 0 0 1-7.95-7L60.8 72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qcsst5bvn) {
  d: path("M206 26.69a8 8 0 0 0-6-2.69H56a8 8 0 0 0-7.94 9l23.15 193a16 16 0 0 0 15.89 14h81.8a16 16 0 0 0 15.89-14.09L207.94 33a8 8 0 0 0-1.94-6.31M191 40l-2.9 24H67.9L65 40Zm-22.1 184H87.1L69.82 80h116.36Z");
}

</style>
