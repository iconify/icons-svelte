<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5xsk27rj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:football-american" {...props}></Icon>
<style>
:global(.c5xsk27rj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 19.5c0-9.5 5.5-15 15-15c0 9.5-5.5 15-15 15m5-5l5-5m-4.75 2.75l2 2m.5-4.5l2 2");
}

</style>
