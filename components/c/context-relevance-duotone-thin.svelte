<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dba5rjonf"/><path class="zl5hlnbpt"/><path class="tdygnegpg"/><path class="nzgezp68k"/><path class="ffw_pwyfz"/><path class="kfdmhd64i"/><path class="nesadtboq"/><path class="mm9i2knor"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:context-relevance-duotone-thin" {...props}></Icon>
<style>
:global(.dba5rjonf) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ffw_pwyfz) {
  d: path("M12.62 3.5a7 7 0 1 1 -5.24 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kfdmhd64i) {
  d: path("m15 15 6 6");
}

:global(.mm9i2knor) {
  d: path("M11.5 7H14v6h-2.5");
}

:global(.nesadtboq) {
  d: path("M8.5 7H6v6h2.5");
}

:global(.nzgezp68k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M11.5 7H14v6h-2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.tdygnegpg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.5 7H6v6h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.zl5hlnbpt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m15 15 6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
