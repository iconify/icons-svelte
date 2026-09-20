<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gqua-bbkg"/><path class="fo_ekznwu"/><path class="v1ku6ibql"/><path class="ltjpzfbzq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:layer-up-outline-regular" {...props}></Icon>
<style>
:global(.fo_ekznwu) {
  d: path("M9.5 4.5 12 2l2.5 2.5");
}

:global(.gqua-bbkg) {
  d: path("M12 4v4.5");
}

:global(.ltjpzfbzq) {
  d: path("M4 19.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v1ku6ibql) {
  d: path("M4 12.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2 2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2");
}

</style>
