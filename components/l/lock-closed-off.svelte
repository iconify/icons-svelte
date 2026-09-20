<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="muiqxrbuk"/><path clip-rule="evenodd" class="dowozdblg"/><path clip-rule="evenodd" class="ajx1t25hz"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:lock-closed-off" {...props}></Icon>
<style>
:global(.ajx1t25hz) {
  fill-rule: evenodd;
  d: path("M14 4a4 4 0 0 0-8 0v5h8zm-2 0v3H8V4a2 2 0 1 1 4 0");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.dowozdblg) {
  fill-rule: evenodd;
  d: path("M13 7H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h6a4 4 0 0 0 4-4v-4a4 4 0 0 0-4-4m-8 4a2 2 0 0 1 2-2h6a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2z");
}

:global(.muiqxrbuk) {
  fill-rule: evenodd;
  d: path("M8 13a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2.5 0a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
