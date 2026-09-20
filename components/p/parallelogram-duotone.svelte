<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="k60hymboh"/><path class="ruvs7dbty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:parallelogram-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k60hymboh) {
  d: path("m239.29 59.28l-64.8 144a8 8 0 0 1-7.3 4.72H24a8 8 0 0 1-7.3-11.28l64.8-144A8 8 0 0 1 88.81 48H232a8 8 0 0 1 7.29 11.28");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ruvs7dbty) {
  d: path("M245.43 47.31A15.94 15.94 0 0 0 232 40H88.81a16 16 0 0 0-14.59 9.43l-64.8 144A16 16 0 0 0 24 216h143.19a16 16 0 0 0 14.59-9.43l64.8-144a16 16 0 0 0-1.15-15.26M167.19 200H24L88.81 56H232Z");
}

</style>
