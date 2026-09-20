<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t5v_djbzx"/><path class="xpzpcfrzo"/><path class="jq9hovbrs"/><path class="yomctlb4k"/><path class="v4hdeje_n"/><path class="u8mhf344d"/><path class="ojw5_mmlr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:music-generate-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jq9hovbrs) {
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
}

:global(.ojw5_mmlr) {
  d: path("M12.5 6 15 8.5");
}

:global(.t5v_djbzx) {
  fill: currentColor;
  d: path("M14 4h5a3 3 0 0 1 3 3v7a3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3V7a3 3 0 0 1 3 -3h5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.u8mhf344d) {
  d: path("M12.5 6v6");
}

:global(.v4hdeje_n) {
  d: path("M8.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.xpzpcfrzo) {
  fill: currentColor;
  d: path("M8.5 12a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.yomctlb4k) {
  d: path("M7 17v4l4 -4");
}

</style>
