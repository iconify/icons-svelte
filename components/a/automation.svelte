<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="goxjtemri"/><path class="uczszbcec"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:automation" {...props}></Icon>
<style>
:global(.goxjtemri) {
  d: path("M6.75 19H14a3.5 3.5 0 0 0 0-7h-4a3.5 3.5 0 0 1 0-7h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.uczszbcec) {
  d: path("M17.5 2.5L20 5l-2.5 2.5M2.75 19a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
