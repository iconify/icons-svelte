<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cpjt28hee"/><path class="qbycr98pd"/><path class="vw4ruuxbu"/><path class="o32gc9b6a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:expand-outline-regular" {...props}></Icon>
<style>
:global(.cpjt28hee) {
  d: path("M4 10V4h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o32gc9b6a) {
  d: path("m20 20 -6 -6");
}

:global(.qbycr98pd) {
  d: path("m4 4 6 6");
}

:global(.vw4ruuxbu) {
  d: path("M14 20h6v-6");
}

</style>
