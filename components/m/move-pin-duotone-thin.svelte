<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p67gkiiyp"/><path class="qad3kqbgr"/><path class="jtt8g10_o"/><path class="c_tajwbcn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:move-pin-duotone-thin" {...props}></Icon>
<style>
:global(.c_tajwbcn) {
  d: path("M12.5 7.5 15 10l-2.5 2.5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jtt8g10_o) {
  d: path("M9 10h6");
}

:global(.p67gkiiyp) {
  fill: currentColor;
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.qad3kqbgr) {
  d: path("M4 10a8 8 0 0 1 16 0l-8 8Z");
}

</style>
