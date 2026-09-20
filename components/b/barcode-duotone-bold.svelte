<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="y1e35w3zw"/><path class="tcpmdzmak"/><path class="euczgzu_d"/><path class="vwjgh8buo"/><path class="g8p8o_zpi"/><path class="nkim8cbjd"/><path class="azgrucbqu"/><path class="j5yfc7b4j"/><path class="btdmtu_xg"/><path class="vckqcjbbb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:barcode-duotone-bold" {...props}></Icon>
<style>
:global(.azgrucbqu) {
  d: path("M7 5v14");
}

:global(.btdmtu_xg) {
  d: path("M14 5v14");
}

:global(.euczgzu_d) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g8p8o_zpi) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j5yfc7b4j) {
  d: path("M11 5v14");
}

:global(.nkim8cbjd) {
  d: path("M4 5v14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tcpmdzmak) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M7 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vckqcjbbb) {
  d: path("M18 5v14");
}

:global(.vwjgh8buo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.y1e35w3zw) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
