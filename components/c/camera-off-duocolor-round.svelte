<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iv4xs0jzj"/><path class="xr2njcb4q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:camera-off-duocolor-round" {...props}></Icon>
<style>
:global(.iv4xs0jzj) {
  stroke-opacity: 0.4;
  d: path("M9.879 10.879a3 3 0 0 0 4.243 4.243M2 3l19 19");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.xr2njcb4q) {
  d: path("M9.54 4.54c.488-.35.995-.54 1.46-.54h2c.64 0 1.36.36 2 1l2 2a4 4 0 0 1 4 4v5m-2.354 3.646A4 4 0 0 1 17 20H7a4 4 0 0 1-4-4v-5c0-1.9 1.325-3.49 3.101-3.899");
}

</style>
