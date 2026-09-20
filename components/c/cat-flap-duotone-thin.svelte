<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucf3ueb9q"/><path class="diipsobkl"/><path class="s1m4z10fj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cat-flap-duotone-thin" {...props}></Icon>
<style>
:global(.diipsobkl) {
  d: path("M5 3v18h14V3Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.s1m4z10fj) {
  d: path("M8 21v-4c0 -2 8 -2 8 0v4");
}

:global(.ucf3ueb9q) {
  fill: currentColor;
  d: path("M5 3v18h14V3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
