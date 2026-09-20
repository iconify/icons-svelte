<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c4my-jbpv"/><path class="qkea2dbiu"/><path class="ha2bk5bpt"/><path class="l7-tgmbes"/><path class="jaql6vb1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:anomaly-data-outline-bold" {...props}></Icon>
<style>
:global(.c4my-jbpv) {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.ha2bk5bpt) {
  d: path("M2 15a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.jaql6vb1s) {
  d: path("m14 14.5 -4 4");
}

:global(.l7-tgmbes) {
  d: path("m10 14.5 4 4");
}

:global(.qkea2dbiu) {
  d: path("M5 6.5h14");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
