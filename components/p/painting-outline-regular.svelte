<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x7x2dubhn"/><path class="yl6rclbxh"/><path class="bvxg1_b9x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:painting-outline-regular" {...props}></Icon>
<style>
:global(.bvxg1_b9x) {
  d: path("m18 6 4 4 -2 2 -4 -4Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.x7x2dubhn) {
  d: path("M3 4v12h12V4Z");
}

:global(.yl6rclbxh) {
  d: path("m13 15 7 -7");
}

</style>
