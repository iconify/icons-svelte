<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ee6zuibqn"/><path class="jb1ewdaxd"/><path class="gw4p-3b_o"/><path class="qb7w1fbvo"/><path class="yxqt_ilaa"/><path class="k11irslia"/><path class="oifr9zbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:relax-duotone-thin" {...props}></Icon>
<style>
:global(.ee6zuibqn) {
  fill: currentColor;
  d: path("M12 6c3 3 3 7 0 10 -3 -3 -3 -7 0 -10");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.gw4p-3b_o) {
  fill: currentColor;
  d: path("M12 16c4 0 7 -3 7 -6 -4 0 -7 3 -7 6");
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

:global(.jb1ewdaxd) {
  fill: currentColor;
  d: path("M12 16c-4 0 -7 -3 -7 -6 4 0 7 3 7 6");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.k11irslia) {
  d: path("M12 16c4 0 7 -3 7 -6 -4 0 -7 3 -7 6");
}

:global(.oifr9zbpt) {
  d: path("M4 20h16");
}

:global(.qb7w1fbvo) {
  d: path("M12 6c3 3 3 7 0 10 -3 -3 -3 -7 0 -10");
}

:global(.yxqt_ilaa) {
  d: path("M12 16c-4 0 -7 -3 -7 -6 4 0 7 3 7 6");
}

</style>
