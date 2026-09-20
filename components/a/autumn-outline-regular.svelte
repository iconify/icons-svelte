<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yf982jbnt"/><path class="j587xtbwm"/><path class="asaq2m23g"/><path class="uih_zvhtv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:autumn-outline-regular" {...props}></Icon>
<style>
:global(.asaq2m23g) {
  d: path("m15 20 4 -4");
}

:global(.j587xtbwm) {
  d: path("m14 15 4 4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.uih_zvhtv) {
  d: path("M4 21h16");
}

:global(.yf982jbnt) {
  d: path("M6 14C6 8 10 4 16 4c0 6 -4 10 -10 10");
}

</style>
