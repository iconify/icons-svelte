<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="axwkrzbmo"/><path class="g_ig5r7qc"/><path class="os75hg6rr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-voice-outline-thin" {...props}></Icon>
<style>
:global(.axwkrzbmo) {
  d: path("m8 8 4 4 -4 4 -4 -4Z");
}

:global(.g_ig5r7qc) {
  d: path("M17.12 9.88a3 3 0 0 1 0 4.24");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.os75hg6rr) {
  d: path("M19.24 7.76a6 6 0 0 1 0 8.5");
}

</style>
