<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhklz97sp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carabiner" {...props}></Icon>
<style>
:global(.qhklz97sp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 9V7.5a5 5 0 0 1 10 0v9a5 5 0 0 1-10 0V15m2.5-6.5l-1 7");
}

</style>
