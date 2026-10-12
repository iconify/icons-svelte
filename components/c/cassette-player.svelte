<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wg45x2bjw"/><rect class="gir1uqqyi"/><circle class="fqdydbc_x"/><circle class="lre_7u_tk"/><path class="jqbcxebvw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:cassette-player" {...props}></Icon>
<style>
:global(.fqdydbc_x) {
  cx: 9.25px;
  cy: 10.75px;
  r: 1.5px;
}

:global(.gir1uqqyi) {
  width: 13.5px;
  height: 8px;
  x: 5.25px;
  y: 6.75px;
  rx: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jqbcxebvw) {
  d: path("M10.75 10.75h2.5m-6.5 9L8 17.25h8l1.25 2.5");
}

:global(.lre_7u_tk) {
  cx: 14.75px;
  cy: 10.75px;
  r: 1.5px;
}

:global(.wg45x2bjw) {
  width: 18.5px;
  height: 15.5px;
  x: 2.75px;
  y: 4.25px;
  rx: 2px;
}

</style>
