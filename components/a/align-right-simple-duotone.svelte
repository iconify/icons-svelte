<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wjm3s7mkj"/><path class="ohuqgpd2o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:align-right-simple-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ohuqgpd2o) {
  d: path("M232 56v144a8 8 0 0 1-16 0V56a8 8 0 0 1 16 0m-32 40v64a16 16 0 0 1-16 16H32a16 16 0 0 1-16-16V96a16 16 0 0 1 16-16h152a16 16 0 0 1 16 16m-16 0H32v64h152Z");
}

:global(.wjm3s7mkj) {
  d: path("M192 96v64a8 8 0 0 1-8 8H32a8 8 0 0 1-8-8V96a8 8 0 0 1 8-8h152a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
