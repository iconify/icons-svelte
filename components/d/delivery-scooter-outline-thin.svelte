<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="skyc_tbew"/><path class="db6bvvb_j"/><path class="olph5u3xh"/><path class="f6186achz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:delivery-scooter-outline-thin" {...props}></Icon>
<style>
:global(.db6bvvb_j) {
  d: path("M16 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

:global(.f6186achz) {
  d: path("M15 8h4");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.olph5u3xh) {
  d: path("m8 16 4 -4h5V8");
}

:global(.skyc_tbew) {
  d: path("M4 16a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

</style>
