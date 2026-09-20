<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="xxiie10rz"/><circle class="qufharbmm"/><circle class="p9rvr-ggk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:division" {...props}></Icon>
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

:global(.xxiie10rz) {
  d: path("M5 11a1 1 0 1 1 0-2h10a1 1 0 1 1 0 2z");
}

</style>
