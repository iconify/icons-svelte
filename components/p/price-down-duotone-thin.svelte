<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rlbrj1bkl"/><path class="u-pn1xbtk"/><path class="vwqgo5sgm"/><path class="xujn_cdhr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:price-down-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rlbrj1bkl) {
  fill: currentColor;
  d: path("M8 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u-pn1xbtk) {
  d: path("M8 7a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.vwqgo5sgm) {
  d: path("M12 14v6.5");
}

:global(.xujn_cdhr) {
  d: path("m9.5 18 2.5 2.5 2.5 -2.5");
}

</style>
