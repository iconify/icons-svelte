<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="o8gvsnbhc"/><path class="bzx-20b7v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-down-duotone" {...props}></Icon>
<style>
:global(.bzx-20b7v) {
  d: path("M207.39 140.94A8 8 0 0 0 200 136h-64V40a8 8 0 0 0-16 0v96H56a8 8 0 0 0-5.66 13.66l72 72a8 8 0 0 0 11.32 0l72-72a8 8 0 0 0 1.73-8.72M128 204.69L75.31 152h105.38Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.o8gvsnbhc) {
  d: path("m200 144l-72 72l-72-72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
