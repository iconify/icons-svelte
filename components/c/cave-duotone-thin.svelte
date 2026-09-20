<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nxy-5-bpb"/><path class="mp3b81b8y"/><path class="sur-qkf7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:cave-duotone-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mp3b81b8y) {
  d: path("M3 21v-9l9 -9 9 9v9Z");
}

:global(.nxy-5-bpb) {
  fill: currentColor;
  d: path("M3 21v-9l9 -9 9 9v9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.sur-qkf7m) {
  d: path("M7 21a5 5 0 0 1 10 0");
}

</style>
