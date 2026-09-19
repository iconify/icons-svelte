<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGlRHKXfFI" class="tmd9zxn2o"/></defs><use href="#SVGlRHKXfFI" class="c-zrgpb5l"/><path class="jd7ptcwmr"/><use href="#SVGlRHKXfFI" class="c-zrgpb5l"/><circle class="gu4lqqbxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:google-meet" {...props}></Icon>
<style>
:global(.c-zrgpb5l) {
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.gu4lqqbxk) {
  cx: 11.148px;
  cy: 32.642px;
  r: 3.102px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

:global(.jd7ptcwmr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.864 18.336l6.426-4.609c1.764-1.259 4.21-.009 4.21 2.163v17.222c0 2.145-2.411 3.403-4.175 2.189l-6.462-4.467");
}

:global(.tmd9zxn2o) {
  fill: none;
  stroke: currentColor;
  d: path("M4.5 18.46c0-5.384 4.365-9.75 9.75-9.75h14.182a4.43 4.43 0 0 1 4.432 4.432v21.716a4.43 4.43 0 0 1-4.432 4.432h-19.5A4.43 4.43 0 0 1 4.5 34.858z");
}

</style>
