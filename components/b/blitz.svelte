<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tgbus8fcc"/><circle class="fdfjs8bxy"/><circle class="s2qkkrvjg"/><circle class="ul99ovb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blitz" {...props}></Icon>
<style>
:global(.fdfjs8bxy) {
  cx: 23.448px;
  cy: 35.176px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.s2qkkrvjg) {
  cx: 11.395px;
  cy: 23.449px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tgbus8fcc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.51 22.819L9.487 8.796a.49.49 0 0 0-.692 0c-7.25 7.25-8.369 18.621-2.672 27.147s16.63 11.843 26.103 7.92s14.86-14 12.86-24.057S34.251 2.5 23.997 2.5a.49.49 0 0 0-.489.489v8.082");
}

:global(.ul99ovb4g) {
  cx: 35.5px;
  cy: 23.449px;
  r: 1.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
