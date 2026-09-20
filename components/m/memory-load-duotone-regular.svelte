<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vul_uwbfe"/><path class="wxx-lxpns"/><path class="ashjd6b6l"/><path class="qvr2dp0fw"/><path class="ysbzwbbjy"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="x58_p1b1n"/><path class="aigfccrzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-load-duotone-regular" {...props}></Icon>
<style>
:global(.aigfccrzm) {
  d: path("M19.5 8.5 22 11l-2.5 2.5");
}

:global(.ashjd6b6l) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldkstzszf) {
  d: path("M3 16h11");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.qvr2dp0fw) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vul_uwbfe) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wxx-lxpns) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.x58_p1b1n) {
  d: path("M17 11h5");
}

:global(.ysbzwbbjy) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M19.5 8.5 22 11l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
