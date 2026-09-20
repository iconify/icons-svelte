<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="u2z_81bft"/><path class="p8m79mb4i"/><path class="m2xst7buy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:key-rotation-outline-regular" {...props}></Icon>
<style>
:global(.d8z1r1beo) {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

:global(.m2xst7buy) {
  d: path("m13 10.5 2 2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p8m79mb4i) {
  d: path("m11 12.5 4 -4");
}

:global(.u2z_81bft) {
  d: path("M7.5 14a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.wzx0dxb2r) {
  d: path("m12 2 3 3 -3 3");
}

</style>
