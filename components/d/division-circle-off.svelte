<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><g transform="translate(3 3)"><path class="xxiie10rz"/><circle class="qufharbmm"/><circle class="p9rvr-ggk"/><path class="xedf9ccsf"/></g><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:division-circle-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.kphejjb8s) {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
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
