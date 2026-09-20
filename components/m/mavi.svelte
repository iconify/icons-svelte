<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="woew6uird"/><circle class="atioxb22d"/><path class="tgrulpzly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mavi" {...props}></Icon>
<style>
:global(.atioxb22d) {
  cx: 36.147px;
  cy: 18.9px;
  r: 0.7px;
  fill: currentColor;
}

:global(.cpk0fnbgt) {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.tgrulpzly) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.147 21.3v5.4m-9.729-2c0 1.1-.9 2-2 2s-2-.9-2-2v-1.3c0-1.1.9-2 2-2s2 .9 2 2m0 3.3v-5.4");
}

:global(.woew6uird) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.18 21.3l-2 5.4l-2-5.4m-17.53 2c0-1.1.9-2 2-2s2 .9 2 2v3.3m-4-5.3v5.4m4-3.4c0-1.1.9-2 2-2s2 .9 2 2v3.3");
}

</style>
