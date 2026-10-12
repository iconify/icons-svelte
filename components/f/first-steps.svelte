<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="izqxsabxo"/><circle class="o314m_b-p"/><path class="d3fum9ynl"/><circle class="fqs7glzwp"/><path class="uop395ctc"/><circle class="hg2m77fua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:first-steps" {...props}></Icon>
<style>
:global(.d3fum9ynl) {
  d: path("M12 10.5c1.25 0 2 1 2 2.5c0 1.25-.5 1.75-.5 2.5S13 17 12 17s-1.25-.75-1.25-1.5s.5-1.25.5-2c0-.5-.75-1-.75-1.75s.75-1.25 1.5-1.25");
}

:global(.fqs7glzwp) {
  cx: 11.25px;
  cy: 8.25px;
  r: 1.25px;
}

:global(.hg2m77fua) {
  cx: 19.25px;
  cy: 4px;
  r: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.izqxsabxo) {
  d: path("M5.25 14.75c-1.25 0-2 1-2 2.5c0 1.25.5 1.75.5 2.5s.5 1.5 1.5 1.5s1.25-.75 1.25-1.5s-.5-1.25-.5-2c0-.5.75-1 .75-1.75s-.75-1.25-1.5-1.25");
}

:global(.o314m_b-p) {
  cx: 6px;
  cy: 12.5px;
  r: 1.25px;
}

:global(.uop395ctc) {
  d: path("M18.5 6.25c-1.25 0-2 1-2 2.5c0 1.25.5 1.75.5 2.5s.5 1.5 1.5 1.5s1.25-.75 1.25-1.5s-.5-1.25-.5-2c0-.5.75-1 .75-1.75s-.75-1.25-1.5-1.25");
}

</style>
