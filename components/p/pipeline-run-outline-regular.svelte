<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vryjydbyu"/><path class="bsy-cccko"/><path class="i0gx68gak"/><path class="m27ljac1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:pipeline-run-outline-regular" {...props}></Icon>
<style>
:global(.bsy-cccko) {
  d: path("m6 9 3 3 -3 3Z");
}

:global(.i0gx68gak) {
  d: path("M14 12h4");
}

:global(.m27ljac1c) {
  d: path("m18 9 3 3 -3 3");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.vryjydbyu) {
  d: path("M2 8a2 2 0 0 1 2 -2h8a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
