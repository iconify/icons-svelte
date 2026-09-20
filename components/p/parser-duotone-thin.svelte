<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tpht7obqo"/><path class="pnaclnbfs"/><path class="n6okm9b5s"/><path class="ud091vbff"/><path class="f-x5yl3mg"/><path class="usiycnb-x"/><path class="hwv-lccbz"/><path class="xyhj-ubbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:parser-duotone-thin" {...props}></Icon>
<style>
:global(.f-x5yl3mg) {
  d: path("M2 12h11");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hwv-lccbz) {
  d: path("M13 7h7");
}

:global(.n6okm9b5s) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 7h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.pnaclnbfs) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tpht7obqo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ud091vbff) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M13 17h7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.usiycnb-x) {
  d: path("M13 7v10");
}

:global(.xyhj-ubbr) {
  d: path("M13 17h7");
}

</style>
