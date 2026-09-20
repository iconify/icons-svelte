<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v-yh3actq"/><path class="q7kpryb3v"/><path class="a8cyhwbdj"/><path class="rw6ho_bav"/><path class="oc7wmvdee"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:calendar-run-outline-regular" {...props}></Icon>
<style>
:global(.a8cyhwbdj) {
  d: path("M16 2v3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.oc7wmvdee) {
  d: path("m10 12 3 3 -3 3Z");
}

:global(.q7kpryb3v) {
  d: path("M8 2v3");
}

:global(.rw6ho_bav) {
  d: path("M2 9h20");
}

:global(.v-yh3actq) {
  d: path("M2 7a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v11a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
