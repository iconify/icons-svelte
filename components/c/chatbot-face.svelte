<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dp-asiefj"/><rect class="ekop3e3sw"/><rect class="t32lf0k7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:chatbot-face" {...props}></Icon>
<style>
:global(.dp-asiefj) {
  d: path("M6 4.75h12A3.25 3.25 0 0 1 21.25 8v6A3.25 3.25 0 0 1 18 17.25h-5.25l-3.9 3.15A.5.5 0 0 1 8 20v-2.75H6A3.25 3.25 0 0 1 2.75 14V8A3.25 3.25 0 0 1 6 4.75");
}

:global(.ekop3e3sw) {
  width: 2.5px;
  height: 3.5px;
  x: 7.75px;
  y: 9px;
  rx: 1.25px;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.t32lf0k7h) {
  width: 2.5px;
  height: 3.5px;
  x: 13.75px;
  y: 9px;
  rx: 1.25px;
}

</style>
