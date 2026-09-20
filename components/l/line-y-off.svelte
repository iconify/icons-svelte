<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="nt3f2bb_i"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:line-y-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.nt3f2bb_i) {
  fill-rule: evenodd;
  d: path("M10 1a1 1 0 0 1 1 1v16a1 1 0 1 1-2 0V2a1 1 0 0 1 1-1");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
