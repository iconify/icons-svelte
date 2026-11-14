<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd3j3a5ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chin-up" {...props}></Icon>
<style>
:global(.nd3j3a5ya) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 11.5h19M9 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m-2.5 6l2 5h7l2-5m-8 5v5m5-5v5");
}

</style>
