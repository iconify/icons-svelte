<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rfpc8ubdp"/><path class="b1ew5xbzw"/><path class="ls68ftbad"/><path class="jvpr04bkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-review-score-outline-thin" {...props}></Icon>
<style>
:global(.b1ew5xbzw) {
  d: path("M14 13v5");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jvpr04bkw) {
  d: path("M21 15v3");
}

:global(.ls68ftbad) {
  d: path("M17.5 9v9");
}

:global(.rfpc8ubdp) {
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
}

</style>
