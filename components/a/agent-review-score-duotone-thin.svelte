<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z9kdgnbgc"/><path class="ffbhbs6nw"/><path class="xg-jjzbeo"/><path class="tv01ftbfi"/><path class="rfpc8ubdp"/><path class="b1ew5xbzw"/><path class="ls68ftbad"/><path class="jvpr04bkw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:agent-review-score-duotone-thin" {...props}></Icon>
<style>
:global(.b1ew5xbzw) {
  d: path("M14 13v5");
}

:global(.ffbhbs6nw) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 13v5");
  opacity: var(--svg-opacity--0-2, 0.2);
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

:global(.tv01ftbfi) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M21 15v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.xg-jjzbeo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17.5 9v9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.z9kdgnbgc) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8.19 8.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
