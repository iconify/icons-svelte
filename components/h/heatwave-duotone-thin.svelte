<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gdy036bip"/><path class="e6h0tjbiq"/><path class="aho1hjbgy"/><path class="qcyhweblp"/><path class="p-qzc1t-u"/><path class="uih_zvhtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heatwave-duotone-thin" {...props}></Icon>
<style>
:global(.aho1hjbgy) {
  d: path("M5 8h2.5");
}

:global(.e6h0tjbiq) {
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.gdy036bip) {
  fill: currentColor;
  d: path("M8 8a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.p-qzc1t-u) {
  d: path("M4 16h8a3 3 0 1 1 -3 3");
}

:global(.qcyhweblp) {
  d: path("M16.5 8H19");
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

</style>
