<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n6wz72bec"/><path class="s-lluab2i"/><path class="vtt_9-b1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:graduation-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.n6wz72bec) {
  d: path("m2 10 4 -4h12l4 4 -4 4H6Z");
}

:global(.s-lluab2i) {
  d: path("M8 14v3l3 3h3l3 -3v-3");
}

:global(.vtt_9-b1s) {
  d: path("M22 10v6");
}

</style>
