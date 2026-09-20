<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sgjb9gifn"/><path class="gjjx1zbjy"/><path class="a5c-jhmhz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:assertion-fail-outline-thin" {...props}></Icon>
<style>
:global(.a5c-jhmhz) {
  d: path("m14 13 -4 4");
}

:global(.gjjx1zbjy) {
  d: path("m10 13 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.sgjb9gifn) {
  d: path("M9 3v7l-5 5v4h16v-4l-5 -5V3Z");
}

</style>
