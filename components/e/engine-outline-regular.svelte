<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b5wqv3c3i"/><path class="nudzxvbtj"/><path class="ojebq65vr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:engine-outline-regular" {...props}></Icon>
<style>
:global(.b5wqv3c3i) {
  d: path("M2 13a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.nudzxvbtj) {
  d: path("M6 11V6h4v5");
}

:global(.ojebq65vr) {
  d: path("M13 11V4h4v7");
}

</style>
