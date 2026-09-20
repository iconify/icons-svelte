<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pus9z-bwo"/><path class="r64foyb_z"/><path class="i6z46-gcv"/><path class="tyihvpb9r"/><path class="kodna-rjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:expert-router-outline-regular" {...props}></Icon>
<style>
:global(.i6z46-gcv) {
  d: path("m13.5 9 3 3");
}

:global(.kodna-rjk) {
  d: path("M13.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pus9z-bwo) {
  d: path("m12 2 3 3 -3 3 -3 -3Z");
}

:global(.r64foyb_z) {
  d: path("m10.5 9 -3 3");
}

:global(.tyihvpb9r) {
  d: path("M2.5 15a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
