<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c9rt-wbve"/><path class="fddb2ca0n"/><path class="uk9xnrm3r"/><path class="xyp2pm_yf"/><path class="fkf_gcbra"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:mtls-outline-thin" {...props}></Icon>
<style>
:global(.c9rt-wbve) {
  d: path("M2 13a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.fddb2ca0n) {
  d: path("M3.5 11a2.5 2.5 0 0 1 5 0");
}

:global(.fkf_gcbra) {
  d: path("M10 15h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uk9xnrm3r) {
  d: path("M14 13a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.xyp2pm_yf) {
  d: path("M15.5 11a2.5 2.5 0 0 1 5 0");
}

</style>
