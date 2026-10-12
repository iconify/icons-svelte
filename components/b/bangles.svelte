<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vlwa6_b_j"/><path class="glc8cfbam"/><path class="ef4cwjf3a"/><path class="vhqqabc1k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:bangles" {...props}></Icon>
<style>
:global(.ef4cwjf3a) {
  d: path("M3.5 13.75a8.5 3.25 0 0 0 17 0");
}

:global(.glc8cfbam) {
  d: path("M3.5 10.75a8.5 3.25 0 0 0 17 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vhqqabc1k) {
  d: path("M3.5 16.75a8.5 3.25 0 0 0 17 0");
}

:global(.vlwa6_b_j) {
  d: path("M3.5 7.5a8.5 3.25 0 1 0 17 0a8.5 3.25 0 1 0-17 0");
}

</style>
