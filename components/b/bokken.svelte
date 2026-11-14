<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssqa36kxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bokken" {...props}></Icon>
<style>
:global(.ssqa36kxp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 20.5l17-17m-15 9l6 6");
}

</style>
