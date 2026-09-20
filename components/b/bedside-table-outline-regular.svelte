<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="codbx8bow"/><path class="y07a50u1t"/><path class="ffwaozrbk"/><path class="tbcegmb1y"/><path class="quvbquwsr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:bedside-table-outline-regular" {...props}></Icon>
<style>
:global(.codbx8bow) {
  d: path("M5 18V7h14v11Z");
}

:global(.ffwaozrbk) {
  d: path("M10 10h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.quvbquwsr) {
  d: path("M17 18v3");
}

:global(.tbcegmb1y) {
  d: path("M7 18v3");
}

:global(.y07a50u1t) {
  d: path("M5 13h14");
}

</style>
