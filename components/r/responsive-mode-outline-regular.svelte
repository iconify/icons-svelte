<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="is1bv_axc"/><path class="cm50vhb_x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:responsive-mode-outline-regular" {...props}></Icon>
<style>
:global(.cm50vhb_x) {
  d: path("M13 9a2 2 0 0 1 2 -2h5a2 2 0 0 1 2 2v6a2 2 0 0 1 -2 2h-5a2 2 0 0 1 -2 -2Z");
}

:global(.is1bv_axc) {
  d: path("M2 6a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v12a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
