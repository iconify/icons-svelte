<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="nxjfyhb_k"/><path class="ic330qb6s"/><rect class="au3mjzb6j"/><rect class="vsb483yfn"/><path class="kzpy_zxbw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:book-stack" {...props}></Icon>
<style>
:global(.au3mjzb6j) {
  width: 15px;
  height: 4px;
  x: 5.25px;
  y: 10.5px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ic330qb6s) {
  d: path("M6.75 17.25v4");
}

:global(.kzpy_zxbw) {
  d: path("M14.25 3.75v4");
}

:global(.nxjfyhb_k) {
  width: 18.5px;
  height: 4px;
  x: 2.75px;
  y: 17.25px;
  rx: 1.25px;
}

:global(.vsb483yfn) {
  width: 14.5px;
  height: 4px;
  x: 3.75px;
  y: 3.75px;
  rx: 1.25px;
}

</style>
