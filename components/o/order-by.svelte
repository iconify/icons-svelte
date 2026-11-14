<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9mxmnbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:order-by" {...props}></Icon>
<style>
:global(.h9mxmnbce) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 3.5h18M3 8h18M3 12.5h11.1m1.9 9v-7m-1.75 1.75L16 14.5l1.75 1.75M20 14.5v7m-1.75-1.75L20 21.5l1.75-1.75");
}

</style>
