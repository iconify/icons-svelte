<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ay2r_ub9d"/><path class="r4_-znbed"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cupcake-sharp" {...props}></Icon>
<style>
:global(.ay2r_ub9d) {
  d: path("M12 9L12 5M15 14L14 22M9 14L10 22M5 14L21 14L21 13C21 10.7909 19.2091 9 17 9L7 9C4.7909 9 3 10.7909 3 13L3 14ZM5 14L7.0001 22L16.9999 22L19 14");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.r4_-znbed) {
  fill: currentColor;
  d: path("M13 2C13 2.5523 12.5523 3 12 3C11.4477 3 11 2.5523 11 2C11 1.4477 11.4477 1 12 1C12.5523 1 13 1.4477 13 2Z");
  stroke: none;
}

</style>
