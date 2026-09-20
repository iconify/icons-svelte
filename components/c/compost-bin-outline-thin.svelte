<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rw4xuxb2g"/><path class="vn6-di86m"/><path class="cfeplwbzd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:compost-bin-outline-thin" {...props}></Icon>
<style>
:global(.cfeplwbzd) {
  d: path("M12 17c-3 0 -4 -2 -4 -4 3 0 4 2 4 4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rw4xuxb2g) {
  d: path("M6 10v10h12V10Z");
}

:global(.vn6-di86m) {
  d: path("M4 7h16");
}

</style>
