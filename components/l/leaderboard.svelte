<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="hqes1jbvt"/><path class="gxj0gh4aj"/><path class="cs_m7lb4s"/><rect class="f0n6kveip"/><path class="y0ccz-u_r"/><path class="wpbe8pmub"/><rect class="pafqijbfu"/><path class="ufcahkbfz"/><path class="izktscztu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:leaderboard" {...props}></Icon>
<style>
:global(.cs_m7lb4s) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 5h7");
}

:global(.f0n6kveip) {
  width: 15px;
  height: 4.5px;
  x: 2.75px;
  y: 9.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.gxj0gh4aj) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 5h.01");
}

:global(.hqes1jbvt) {
  width: 18.5px;
  height: 4.5px;
  x: 2.75px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.izktscztu) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 19h3");
}

:global(.pafqijbfu) {
  width: 11.5px;
  height: 4.5px;
  x: 2.75px;
  y: 16.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 1.5px;
}

:global(.ufcahkbfz) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 19h.01");
}

:global(.wpbe8pmub) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 12H14");
}

:global(.y0ccz-u_r) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 12h.01");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
