<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bz5wrnbix"/><path clip-rule="evenodd" class="ewjqafbxw"/><path clip-rule="evenodd" class="atnh38bjm"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:arrow-down-off" {...props}></Icon>
<style>
:global(.atnh38bjm) {
  fill-rule: evenodd;
  d: path("M10 14a1 1 0 0 1-1-1V5a1 1 0 1 1 2 0v8a1 1 0 0 1-1 1");
}

:global(.bz5wrnbix) {
  fill-rule: evenodd;
  d: path("M14.768 11.027a1 1 0 0 1-.128 1.408l-4 3.333a1 1 0 0 1-1.28-1.536l4-3.334a1 1 0 0 1 1.408.129");
}

:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.ewjqafbxw) {
  fill-rule: evenodd;
  d: path("M5.232 11.027a1 1 0 0 1 1.408-.129l4 3.334a1 1 0 1 1-1.28 1.536l-4-3.333a1 1 0 0 1-.128-1.408");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
