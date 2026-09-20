<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="naqgwob8x"/><path class="j9btq3bkp"/><path class="vl1iqdb4x"/><path class="q8-3-v_8e"/><path class="g5j0ssbtg"/><path class="fforjyb_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:exit-ramp-duotone-regular" {...props}></Icon>
<style>
:global(.fforjyb_s) {
  d: path("M15.5 16H19v-3.5");
}

:global(.g5j0ssbtg) {
  d: path("M6 10h7l6 6");
}

:global(.j9btq3bkp) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 10h7l6 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.naqgwob8x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 2v19");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.q8-3-v_8e) {
  d: path("M6 2v19");
}

:global(.vl1iqdb4x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15.5 16H19v-3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
