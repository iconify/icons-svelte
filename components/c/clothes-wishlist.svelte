<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nitvwozao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:clothes-wishlist" {...props}></Icon>
<style>
:global(.nitvwozao) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 4.25A2.25 2.25 0 1 1 12 6.5m.817.431L16.5 8.875a1.26 1.26 0 0 1-.588 2.375H8.088A1.26 1.26 0 0 1 7.5 8.875l3.683-1.944a1.75 1.75 0 0 1 1.634 0M12 21.5L8 18a2.5 2.5 0 0 1 4-3a2.5 2.5 0 0 1 4 3Z");
}

</style>
