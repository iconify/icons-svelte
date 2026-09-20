<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="h4br4z40f"/><path class="hrjx5ybsq"/><path class="e0fatccfd"/><path class="pkakcnb0w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:resistor-outline-thin" {...props}></Icon>
<style>
:global(.e0fatccfd) {
  d: path("M18 12h4");
}

:global(.h4br4z40f) {
  d: path("M2 12h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hrjx5ybsq) {
  d: path("M6 8h12v8H6Z");
}

:global(.pkakcnb0w) {
  d: path("m8 14 3 -3 3 3 2 -2");
}

</style>
