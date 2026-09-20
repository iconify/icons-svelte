<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="egu3z3b4k"/><path class="w5jthw4-k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:person-simple-tai-chi-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.egu3z3b4k) {
  d: path("M152 48a24 24 0 1 1-24-24a24 24 0 0 1 24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w5jthw4-k) {
  d: path("M128 80a32 32 0 1 0-32-32a32 32 0 0 0 32 32m0-48a16 16 0 1 1-16 16a16 16 0 0 1 16-16m96 72a8 8 0 0 1-8 8h-80v26.72l51.15 21.93A8 8 0 0 1 192 168v48a8 8 0 0 1-16 0v-42.72l-46.45-19.91L53.35 222a8 8 0 1 1-10.7-11.9L120 140.44V112H40a8 8 0 0 1 0-16h176a8 8 0 0 1 8 8");
}

</style>
