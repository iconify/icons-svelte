<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j47t6fbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:expand" {...props}></Icon>
<style>
:global(.j47t6fbjg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14 10l5.5-5.5m-5 0h5v5M14 14l5.5 5.5m0-5v5h-5M10 14l-5.5 5.5m5 0h-5v-5M10 10L4.5 4.5m0 5v-5h5");
}

</style>
