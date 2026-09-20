<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="n8lvvzixm"/><path class="x194u0bty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrow-fat-line-left-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.n8lvvzixm) {
  d: path("M184 80v96h-64v48l-96-96l96-96v48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x194u0bty) {
  d: path("M184 72h-56V32a8 8 0 0 0-13.66-5.66l-96 96a8 8 0 0 0 0 11.32l96 96A8 8 0 0 0 128 224v-40h56a8 8 0 0 0 8-8V80a8 8 0 0 0-8-8m-8 96h-56a8 8 0 0 0-8 8v28.69L35.31 128L112 51.31V80a8 8 0 0 0 8 8h56Zm48-88v96a8 8 0 0 1-16 0V80a8 8 0 0 1 16 0");
}

</style>
