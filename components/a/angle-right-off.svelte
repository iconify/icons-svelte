<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ze6dckb4b"/><path class="lhz09l8zb"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:angle-right-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.lhz09l8zb) {
  d: path("M6.732 4.64a1 1 0 0 1 1.536-1.28l5 6a1 1 0 1 1-1.536 1.28z");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.ze6dckb4b) {
  d: path("M11.732 9.36a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 1 1-1.536-1.28z");
}

</style>
