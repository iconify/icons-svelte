<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="og70b5ofm"/><path class="g4tju8tjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:danger-skull" {...props}></Icon>
<style>
:global(.g4tju8tjf) {
  d: path("M6.5 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-5.25 5.25h7.5m-5 0v3m2.5-3v3");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.og70b5ofm) {
  d: path("M3 12a9 8 0 0 1 18 0v2.75l-3 2v3.5H6v-3.5l-3-2Z");
}

</style>
