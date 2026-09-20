<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jzln5b9mk"/><path class="pmeincb2n"/><path class="q2fp4ccin"/><path class="hh49znbxn"/><path class="w-wacblka"/><path class="xz1gkzbgx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:group-tour-outline-regular" {...props}></Icon>
<style>
:global(.hh49znbxn) {
  d: path("M3 19a4 4 0 0 1 8 0");
}

:global(.jzln5b9mk) {
  d: path("M4 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pmeincb2n) {
  d: path("M9.5 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.q2fp4ccin) {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.w-wacblka) {
  d: path("M8.5 19a4 4 0 0 1 8 0");
}

:global(.xz1gkzbgx) {
  d: path("M14 19a4 4 0 0 1 8 0");
}

</style>
