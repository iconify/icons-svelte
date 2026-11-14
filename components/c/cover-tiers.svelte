<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mqml52bmn"/><path class="tg0w2pzls"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cover-tiers" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.mqml52bmn) {
  d: path("M2.5 21v-4h6.25v-3.75h5.75V9.5h7V21Z");
}

:global(.tg0w2pzls) {
  d: path("M14.5 6a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0M18 4.5v3");
}

</style>
