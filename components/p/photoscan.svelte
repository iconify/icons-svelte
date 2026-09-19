<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<rect class="bubkcubok"/><path class="nah166wmv"/><path class="jfkky2nkl"/><path class="agoo6krfn"/><path class="kqzw_4b-a"/><circle class="rgl38-b5p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:photoscan" {...props}></Icon>
<style>
:global(.agoo6krfn) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.762 8.222a8 8 0 0 0 11.24 11.24");
}

:global(.bubkcubok) {
  width: 31px;
  height: 36px;
  x: 8.5px;
  y: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

:global(.jfkky2nkl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.173 13.197a8.001 8.001 0 1 0 10.935 10.701");
}

:global(.kqzw_4b-a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.866 9.628a8.001 8.001 0 1 0 10.73 10.729");
}

:global(.nah166wmv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 8.224h24v24H12z");
}

:global(.rgl38-b5p) {
  cx: 31.027px;
  cy: 13.197px;
  r: 2.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
