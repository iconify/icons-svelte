<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0n63pb2v"/><path class="zzd_26bmd"/><path class="fowv_cb8z"/><path class="fozhwebbv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heap-dump-outline-regular" {...props}></Icon>
<style>
:global(.fowv_cb8z) {
  d: path("M13.5 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.fozhwebbv) {
  d: path("M10 6a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.n0n63pb2v) {
  d: path("M4 15v4h16v-4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.zzd_26bmd) {
  d: path("M6.5 11a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
