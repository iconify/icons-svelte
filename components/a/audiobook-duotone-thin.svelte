<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b6-9mc2ec"/><path class="jg7wewb9v"/><path class="lhanhxbya"/><path class="fse74oemj"/><path class="ocopvj5ps"/><path class="ic00xab8f"/><path class="cb9u5zbqi"/><path class="xyckaabnm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:audiobook-duotone-thin" {...props}></Icon>
<style>
:global(.b6-9mc2ec) {
  fill: currentColor;
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.cb9u5zbqi) {
  d: path("M2 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fse74oemj) {
  d: path("M6 10a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v9a2 2 0 0 1 -2 2H8a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic00xab8f) {
  d: path("M4 12a8 8 0 0 1 16 0");
}

:global(.jg7wewb9v) {
  fill: currentColor;
  d: path("M2 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.lhanhxbya) {
  fill: currentColor;
  d: path("M18 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.ocopvj5ps) {
  d: path("M9 8v13");
}

:global(.xyckaabnm) {
  d: path("M18 15a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
