<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gw6llof_t"/><path class="ax2a_u0ki"/><path class="di4tvaczb"/><path class="jdgij1_su"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-left-right-line-duotone" {...props}></Icon>
<style>
:global(.ax2a_u0ki) {
  d: path("M18 9L21 12L15 18");
}

:global(.di4tvaczb) {
  d: path("M9 18L3 12L9 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.gw6llof_t) {
  d: path("M15 18L21 12L15 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jdgij1_su) {
  d: path("M6 9L3 12L9 18");
}

</style>
