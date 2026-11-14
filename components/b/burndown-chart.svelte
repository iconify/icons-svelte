<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4mdenbgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:burndown-chart" {...props}></Icon>
<style>
:global(.k4mdenbgt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v17h17M7 6.5l4.5 4.5l3 1.5l4 4.5");
}

</style>
