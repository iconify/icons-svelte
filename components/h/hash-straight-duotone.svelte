<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="zm5wl-1qw"/><path class="u86-ippmn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:hash-straight-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.u86-ippmn) {
  d: path("M216 152h-48v-48h48a8 8 0 0 0 0-16h-48V40a8 8 0 0 0-16 0v48h-48V40a8 8 0 0 0-16 0v48H40a8 8 0 0 0 0 16h48v48H40a8 8 0 0 0 0 16h48v48a8 8 0 0 0 16 0v-48h48v48a8 8 0 0 0 16 0v-48h48a8 8 0 0 0 0-16m-112 0v-48h48v48Z");
}

:global(.zm5wl-1qw) {
  d: path("M160 96v64H96V96Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
