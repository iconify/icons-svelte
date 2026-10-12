<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5y5j4b6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:playback-speed" {...props}></Icon>
<style>
:global(.y5y5j4b6u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.79 5.27l9.92 5.96q1.29.77 0 1.54l-9.92 5.96Q8.5 19.5 8.5 18V6q0-1.5 1.29-.73M2.75 8.25h3m-3 3.75h2m-2 3.75h3");
}

</style>
