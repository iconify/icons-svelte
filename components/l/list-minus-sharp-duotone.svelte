<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="in4f_nj7p"/><path class="dyc7ambzy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-minus-sharp-duotone" {...props}></Icon>
<style>
:global(.dyc7ambzy) {
  d: path("M1 18L7 18M9 18L15 18M17 18L23 18");
}

:global(.gp_8x1bzb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.in4f_nj7p) {
  stroke-opacity: 0.4;
  d: path("M1 6L23 6M1 12L23 12");
}

</style>
