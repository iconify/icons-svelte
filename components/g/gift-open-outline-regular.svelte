<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="irf6xy5kk"/><path class="x50q_4bdr"/><path class="i7iskytip"/><path class="ege_q3bkn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:gift-open-outline-regular" {...props}></Icon>
<style>
:global(.ege_q3bkn) {
  d: path("m8 5 2 -2");
}

:global(.i7iskytip) {
  d: path("m13 6 3 -3");
}

:global(.irf6xy5kk) {
  d: path("M5 13v8h14v-8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x50q_4bdr) {
  d: path("M3 10h18");
}

</style>
