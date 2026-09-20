<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xm60vxbgs"/><path class="ys-dg812g"/><path class="q1cfkyb_k"/><path class="hhn28yosy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:armchair-outline-regular" {...props}></Icon>
<style>
:global(.hhn28yosy) {
  d: path("M21 20v-8h-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q1cfkyb_k) {
  d: path("M3 20v-8h4");
}

:global(.xm60vxbgs) {
  d: path("M7 16V5h10v11");
}

:global(.ys-dg812g) {
  d: path("M3 16h18");
}

</style>
