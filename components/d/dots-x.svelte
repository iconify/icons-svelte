<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><circle class="zm0the13b"/><circle class="ehbqml5ic"/><circle class="z4qfeoj9o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:dots-x" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ehbqml5ic) {
  cx: 10px;
  cy: 10px;
  r: 2px;
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
