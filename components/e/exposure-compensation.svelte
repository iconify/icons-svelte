<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0y0t0run"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:exposure-compensation" {...props}></Icon>
<style>
:global(.t0y0t0run) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.625 3.5h4.75A6.125 6.125 0 0 1 20.5 9.625v4.75a6.125 6.125 0 0 1-6.125 6.125h-4.75A6.125 6.125 0 0 1 3.5 14.375v-4.75A6.125 6.125 0 0 1 9.625 3.5M3.5 20.5l17-17M6.5 9H11M8.75 6.75v4.5M13 15h4.5");
}

</style>
