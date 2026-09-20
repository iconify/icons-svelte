<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="xxiie10rz"/><circle class="qufharbmm"/><circle class="p9rvr-ggk"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:division-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.p9rvr-ggk) {
  cx: 10px;
  cy: 14.5px;
  r: 1.5px;
}

:global(.qufharbmm) {
  cx: 10px;
  cy: 5.5px;
  r: 1.5px;
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.xxiie10rz) {
  d: path("M5 11a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2z");
}

</style>
