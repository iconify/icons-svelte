<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tybvy45xk"/><path class="p5t70bc9p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-todo-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.p5t70bc9p) {
  d: path("M11 7L23 7M11 18L23 18M1.7071 17.7071L4 20L8.2929 15.7071");
}

:global(.tybvy45xk) {
  fill: currentColor;
  d: path("M2 3L8 3C8.5523 3 9 3.4477 9 4L9 10C9 10.5523 8.5523 11 8 11L2 11C1.4477 11 1 10.5523 1 10L1 4C1 3.4477 1.4477 3 2 3Z");
  stroke: none;
}

</style>
