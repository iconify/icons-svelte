<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c54duacdo"/><path class="es4r-tbix"/><path class="iogxcvc1e"/><path class="xiot9nbkk"/><path class="cg-i-7_rc"/><path class="nrqy16b7j"/><path class="qnmmmsbha"/><path class="ldkstzszf"/><path class="x58_p1b1n"/><path class="aigfccrzm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-load-duotone-bold" {...props}></Icon>
<style>
:global(.aigfccrzm) {
  d: path("M19.5 8.5 22 11l-2.5 2.5");
}

:global(.c54duacdo) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 6h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cg-i-7_rc) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19.5 8.5 22 11l-2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.es4r-tbix) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 11h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.iogxcvc1e) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 16h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.ldkstzszf) {
  d: path("M3 16h11");
}

:global(.nrqy16b7j) {
  d: path("M3 6h11");
}

:global(.qnmmmsbha) {
  d: path("M3 11h11");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.x58_p1b1n) {
  d: path("M17 11h5");
}

:global(.xiot9nbkk) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M17 11h5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
