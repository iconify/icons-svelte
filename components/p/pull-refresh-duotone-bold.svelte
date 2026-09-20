<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="eyr16rboh"/><path class="glg_nzxdo"/><path class="gk4de-b1j"/><path class="xaz90clio"/><path class="edr2cqsrt"/><path class="juej44_6j"/><path class="yih0nfb7c"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pull-refresh-duotone-bold" {...props}></Icon>
<style>
:global(.edr2cqsrt) {
  d: path("M9.5 3 12 5.5 14.5 3");
}

:global(.eyr16rboh) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 3 12 5.5 14.5 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.gk4de-b1j) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 14h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.glg_nzxdo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 7.5 12 10l2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.juej44_6j) {
  d: path("M9.5 7.5 12 10l2.5 -2.5");
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.xaz90clio) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.yih0nfb7c) {
  d: path("M3 14h18");
}

</style>
