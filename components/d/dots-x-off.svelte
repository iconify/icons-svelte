<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="zm0the13b"/><circle class="ehbqml5ic"/><circle class="z4qfeoj9o"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:dots-x-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ehbqml5ic) {
  cx: 10px;
  cy: 10px;
  r: 2px;
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.z4qfeoj9o) {
  cx: 15px;
  cy: 10px;
  r: 2px;
}

:global(.zm0the13b) {
  cx: 5px;
  cy: 10px;
  r: 2px;
}

</style>
