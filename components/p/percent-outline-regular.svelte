<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="emvotkb4z"/><path class="nnfdo4bja"/><path class="j2hnp9b4t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:percent-outline-regular" {...props}></Icon>
<style>
:global(.emvotkb4z) {
  d: path("M4 20 20 4");
}

:global(.j2hnp9b4t) {
  d: path("M15 17a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nnfdo4bja) {
  d: path("M5 7a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
