<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tf45nxf-h"/><path class="h29js23-i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-collapse-duotone" {...props}></Icon>
<style>
:global(.h29js23-i) {
  d: path("M13 6H21M13 12H21M13 18H21");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.tf45nxf-h) {
  stroke-opacity: 0.4;
  d: path("M6 3V10M3 7L6 10L9 7M6 21V14M3 17L6 14L9 17");
}

</style>
