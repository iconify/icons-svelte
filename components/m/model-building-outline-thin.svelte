<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eq8p65fcb"/><path class="r7xk8o29f"/><path class="of_dlbc-j"/><path class="ns-291-6d"/><path class="x4bmljlar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:model-building-outline-thin" {...props}></Icon>
<style>
:global(.eq8p65fcb) {
  d: path("M4 4v16h16V4Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ns-291-6d) {
  d: path("m15 8 3 3 -3 3");
}

:global(.of_dlbc-j) {
  d: path("M6 9a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.r7xk8o29f) {
  d: path("M12 4v16");
}

:global(.x4bmljlar) {
  d: path("M6 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
