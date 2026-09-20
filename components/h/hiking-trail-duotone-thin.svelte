<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="l2el_bbjq"/><path class="uzdw-e_ie"/><path class="hca97abqo"/><path class="n-6o3ubsz"/><path class="bm-eye5hu"/><path class="r8eifzb3i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:hiking-trail-duotone-thin" {...props}></Icon>
<style>
:global(.bm-eye5hu) {
  d: path("M7 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.hca97abqo) {
  fill: currentColor;
  d: path("M12 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.l2el_bbjq) {
  fill: currentColor;
  d: path("M8 4a4 4 0 0 1 8 0v9a4 4 0 0 1 -8 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.n-6o3ubsz) {
  d: path("M8 4a4 4 0 0 1 8 0v9a4 4 0 0 1 -8 0Z");
}

:global(.r8eifzb3i) {
  d: path("M12 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.uzdw-e_ie) {
  fill: currentColor;
  d: path("M7 18a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
