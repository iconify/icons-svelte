<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nzq45nc7z"/><path class="znfuzdoyp"/><path class="hfzq5f4-k"/><path class="l_69zfb0c"/><path class="rkhcgsbdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:metal-detecting-duotone-thin" {...props}></Icon>
<style>
:global(.hfzq5f4-k) {
  d: path("M7 9h6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l_69zfb0c) {
  d: path("M9 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.nzq45nc7z) {
  fill: currentColor;
  d: path("M9 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.rkhcgsbdl) {
  d: path("M3 19h18");
}

:global(.znfuzdoyp) {
  d: path("M7 3v6");
}

</style>
