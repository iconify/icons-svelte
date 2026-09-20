<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="pzn6r9beo"/><path clip-rule="evenodd" class="lc-cpx7hx"/><path clip-rule="evenodd" class="k1qsxqwde"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:clock-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k1qsxqwde) {
  fill-rule: evenodd;
  d: path("M14 10a1 1 0 0 1-1 1h-3a1 1 0 1 1 0-2h3a1 1 0 0 1 1 1");
}

:global(.lc-cpx7hx) {
  fill-rule: evenodd;
  d: path("M10 6a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1");
}

:global(.pzn6r9beo) {
  fill-rule: evenodd;
  d: path("M10 4a6 6 0 1 0 0 12a6 6 0 0 0 0-12m-8 6a8 8 0 1 1 16 0a8 8 0 0 1-16 0");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
