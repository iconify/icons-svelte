<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u3vj6iq1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chart-scatter" {...props}></Icon>
<style>
:global(.u3vj6iq1f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5v17h17M8 15.5h.01m2.49-6h.01M13 14h.01m2.49-7h.01m2.99 4.5h.01M8 6h.01");
}

</style>
