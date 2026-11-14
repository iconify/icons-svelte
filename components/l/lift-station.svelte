<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xpjtf0b5l"/><path class="ls594hb3c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lift-station" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ls594hb3c) {
  d: path("M11.5 16h1a1.5 1.5 0 0 1 1.5 1.5v2a1.5 1.5 0 0 1-1.5 1.5h-1a1.5 1.5 0 0 1-1.5-1.5v-2a1.5 1.5 0 0 1 1.5-1.5");
}

:global(.xpjtf0b5l) {
  d: path("M2.5 3h19M10 5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m2 2v2m-7.177 4.486l6.25-3.906a1.75 1.75 0 0 1 1.854 0l6.25 3.906A1.75 1.75 0 0 1 20 14.97v4.28A1.75 1.75 0 0 1 18.25 21H5.75A1.75 1.75 0 0 1 4 19.25v-4.28a1.75 1.75 0 0 1 .823-1.484");
}

</style>
