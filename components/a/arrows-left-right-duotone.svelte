<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="d-4jj0bwp"/><path class="bmady2bzt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:arrows-left-right-duotone" {...props}></Icon>
<style>
:global(.bmady2bzt) {
  d: path("m213.66 181.66l-32 32a8 8 0 0 1-11.32-11.32L188.69 184H48a8 8 0 0 1 0-16h140.69l-18.35-18.34a8 8 0 0 1 11.32-11.32l32 32a8 8 0 0 1 0 11.32m-139.32-64a8 8 0 0 0 11.32-11.32L67.31 88H208a8 8 0 0 0 0-16H67.31l18.35-18.34a8 8 0 0 0-11.32-11.32l-32 32a8 8 0 0 0 0 11.32Z");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d-4jj0bwp) {
  d: path("M208 80v96H48V80Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
