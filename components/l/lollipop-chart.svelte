<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k7fw2fx5y"/><circle class="c_pvp7bsw"/><circle class="f7q4j1b4c"/><circle class="n7wblqmuf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:lollipop-chart" {...props}></Icon>
<style>
:global(.c_pvp7bsw) {
  cx: 8.5px;
  cy: 11.5px;
  r: 1.75px;
}

:global(.f7q4j1b4c) {
  cx: 13.75px;
  cy: 6px;
  r: 1.75px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k7fw2fx5y) {
  d: path("M3.75 3.75v14.5a2 2 0 0 0 2 2h14.5m-11.75-3v-4m5.25 4v-9.5m5.25 9.5V14.5");
}

:global(.n7wblqmuf) {
  cx: 19px;
  cy: 12.75px;
  r: 1.75px;
}

</style>
