<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="lq8ad-lob"/><path class="kjk2ocb0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:battery-full-sharp-fill" {...props}></Icon>
<style>
:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.kjk2ocb0m) {
  d: path("M22 8.5L22 15.5");
}

:global(.lq8ad-lob) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 5L18 5C18.5523 5 19 5.4477 19 6L19 18C19 18.5523 18.5523 19 18 19L2 19C1.4477 19 1 18.5523 1 18L1 6C1 5.4477 1.4477 5 2 5ZM7 9L7 15L5 15L5 9L7 9ZM11 9L11 15L9 15L9 9L11 9ZM15 9L15 15L13 15L13 9L15 9Z");
  stroke: none;
}

</style>
