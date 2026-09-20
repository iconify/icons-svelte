<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vhnbtvbtn"/><path class="d4rfzbb0c"/><path class="ys-dg812g"/><path class="wtfq6b2ta"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:config-drift-outline-thin" {...props}></Icon>
<style>
:global(.d4rfzbb0c) {
  d: path("M6 8a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vhnbtvbtn) {
  d: path("M3 8h18");
}

:global(.wtfq6b2ta) {
  d: path("M14 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
