<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecw_k6bqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:grand-total" {...props}></Icon>
<style>
:global(.ecw_k6bqf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17 3H7l5 5.75l-5 5.75h10m-12 3h14m-14 3h14");
}

</style>
