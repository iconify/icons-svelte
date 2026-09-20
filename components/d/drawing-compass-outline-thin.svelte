<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fnf6pdbdu"/><path class="xwissob6k"/><path class="d4f9j2bku"/><path class="x1_r36phd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:drawing-compass-outline-thin" {...props}></Icon>
<style>
:global(.d4f9j2bku) {
  d: path("m12 9 6 6v4");
}

:global(.fnf6pdbdu) {
  d: path("M12 3v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x1_r36phd) {
  d: path("M9 12h6");
}

:global(.xwissob6k) {
  d: path("m12 9 -6 6v4");
}

</style>
