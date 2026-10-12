<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k012gh4pj"/><rect class="gro0y62ip"/><path class="smvo6hbmn"/><rect class="qm0sv0bkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:peeler" {...props}></Icon>
<style>
:global(.gro0y62ip) {
  width: 8.5px;
  height: 5px;
  x: 7.75px;
  y: 2.75px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.k012gh4pj) {
  d: path("M4.75 2.75v5L12 15l7.25-7.25v-5");
}

:global(.qm0sv0bkw) {
  width: 3.5px;
  height: 6.25px;
  x: 10.25px;
  y: 15px;
  rx: 0.75px;
}

:global(.smvo6hbmn) {
  d: path("M10 5.25h4");
}

</style>
