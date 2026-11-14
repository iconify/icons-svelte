<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm4c47wea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mountain-climbing" {...props}></Icon>
<style>
:global(.tm4c47wea) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19L9 8l4 6l2.5-3.5l6 8.5ZM18 7V3.5L21 5h-3");
}

</style>
