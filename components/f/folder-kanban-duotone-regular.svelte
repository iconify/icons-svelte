<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r0jamibkm"/><path class="bn_pu6j-z"/><path class="xgrnk0bjr"/><path class="mxzk029nb"/><path class="trdlwwbvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:folder-kanban-duotone-regular" {...props}></Icon>
<style>
:global(.bn_pu6j-z) {
  d: path("M20 7v13H4V4h5l3 3h4");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r0jamibkm) {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.trdlwwbvq) {
  d: path("M15 10v5");
}

:global(.xgrnk0bjr) {
  d: path("M9 10v7");
}

</style>
