<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="vkw1_cp5z"/><path class="s7j6rpbhs"/><path class="h8cuisb-x"/><path class="pdm45_o_b"/><path class="w_otj1bev"/><path class="e1uudcbua"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:heart-duotone-regular" {...props}></Icon>
<style>
:global(.e1uudcbua) {
  d: path("m4 9 8 8 8 -8");
}

:global(.h8cuisb-x) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 9 8 8 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.pdm45_o_b) {
  d: path("M4 9a4 4 0 0 1 8 0");
}

:global(.s7j6rpbhs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.vkw1_cp5z) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9a4 4 0 0 1 8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.w_otj1bev) {
  d: path("M12 9a4 4 0 0 1 8 0");
}

</style>
