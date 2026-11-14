<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zpkozqbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bucket" {...props}></Icon>
<style>
:global(.zpkozqbqm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 8h17l-2.25 13.5H5.75Zm0 0c0-6.25 17-6.25 17 0");
}

</style>
