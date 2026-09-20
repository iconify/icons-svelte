<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vfo57uyzf"/><path class="q2fp4ccin"/><path class="p-6zwabto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:byte-pair-outline-regular" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p-6zwabto) {
  d: path("M6 14v3h12v-3");
}

:global(.q2fp4ccin) {
  d: path("M15 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

:global(.vfo57uyzf) {
  d: path("M3 9a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
