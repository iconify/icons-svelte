<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="w9jsdsb8y"/><path clip-rule="evenodd" class="wf-0hpb3d"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:list-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.w9jsdsb8y) {
  d: path("M6.5 6a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 4a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0m0 4a1.5 1.5 0 1 1-3 0a1.5 1.5 0 0 1 3 0");
}

:global(.wf-0hpb3d) {
  fill-rule: evenodd;
  d: path("M7.5 6a1 1 0 0 1 1-1h7a1 1 0 1 1 0 2h-7a1 1 0 0 1-1-1m0 4a1 1 0 0 1 1-1h7a1 1 0 1 1 0 2h-7a1 1 0 0 1-1-1m0 4a1 1 0 0 1 1-1h7a1 1 0 1 1 0 2h-7a1 1 0 0 1-1-1");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
