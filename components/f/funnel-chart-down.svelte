<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyy8rrblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:funnel-chart-down" {...props}></Icon>
<style>
:global(.tyy8rrblj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.241 18.475L9 20.5V11L3 3.5h16L13 11v5.595m5-2.095v7m-3-3l3 3l3-3");
}

</style>
