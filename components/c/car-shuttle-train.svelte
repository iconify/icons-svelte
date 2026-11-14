<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zse-c3bxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:car-shuttle-train" {...props}></Icon>
<style>
:global(.zse-c3bxc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 11V8.5L7 5h7.5l3 3.5h2V11Zm-2 3h19M3.75 16.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m12 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
