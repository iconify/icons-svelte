<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lqedrkb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:currency-dirham" {...props}></Icon>
<style>
:global(.lqedrkb-n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 5h3c4.5 0 7 3 7 7s-2.5 7-7 7H8Zm-3 5h15M5 14h15");
}

</style>
