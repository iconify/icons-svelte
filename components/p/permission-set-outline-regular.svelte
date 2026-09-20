<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xfs8wlfhn"/><path class="ygr1bbcag"/><path class="mo1bh2_2m"/><path class="zpdz8rbaf"/><path class="s9itk2b_k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:permission-set-outline-regular" {...props}></Icon>
<style>
:global(.mo1bh2_2m) {
  d: path("M9 12.5h6");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.s9itk2b_k) {
  d: path("M9 18.5h6");
}

:global(.xfs8wlfhn) {
  d: path("M5 11.5a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

:global(.ygr1bbcag) {
  d: path("M8 9.5a4 4 0 0 1 8 0");
}

:global(.zpdz8rbaf) {
  d: path("M9 15.5h6");
}

</style>
