<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1jtzdnst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:diamond-small" {...props}></Icon>
<style>
:global(.w1jtzdnst) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.237 7.737l3.026 3.026a1.75 1.75 0 0 1 0 2.474l-3.026 3.026a1.75 1.75 0 0 1-2.474 0l-3.026-3.026a1.75 1.75 0 0 1 0-2.474l3.026-3.026a1.75 1.75 0 0 1 2.474 0");
}

</style>
