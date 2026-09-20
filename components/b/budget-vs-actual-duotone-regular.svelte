<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pga6n1bci"/><path class="iepbicc-q"/><path class="frt61khkq"/><path class="p9olxmbrk"/><path class="jkuojibnm"/><path class="nn2mbucfp"/><path class="wwyi7ubez"/><path class="om9c7ck0x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:budget-vs-actual-duotone-regular" {...props}></Icon>
<style>
:global(.frt61khkq) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14 20v-6h5v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iepbicc-q) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M5 20V8h5v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.nn2mbucfp) {
  d: path("M5 20V8h5v12");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.om9c7ck0x) {
  d: path("M13 8h7");
}

:global(.p9olxmbrk) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 8h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pga6n1bci) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wwyi7ubez) {
  d: path("M14 20v-6h5v6");
}

</style>
