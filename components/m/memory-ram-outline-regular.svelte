<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x2d2kybwe"/><path class="l5z6qsb5o"/><path class="fmlaifbpn"/><path class="mmtudb-4h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:memory-ram-outline-regular" {...props}></Icon>
<style>
:global(.fmlaifbpn) {
  d: path("M12 16v4");
}

:global(.l5z6qsb5o) {
  d: path("M7 16v4");
}

:global(.mmtudb-4h) {
  d: path("M17 16v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x2d2kybwe) {
  d: path("M3 8a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

</style>
