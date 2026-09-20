<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x44d32bzm"/><path class="i8nljac2s"/><path class="zky2rs_uy"/><path class="wuk2mlziz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:peeler-outline-regular" {...props}></Icon>
<style>
:global(.i8nljac2s) {
  d: path("M7 9v10");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.wuk2mlziz) {
  d: path("M7 19h10");
}

:global(.x44d32bzm) {
  d: path("M5 6a3 3 0 0 1 3 -3h8a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H8a3 3 0 0 1 -3 -3");
}

:global(.zky2rs_uy) {
  d: path("M17 9v10");
}

</style>
