<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vop1yybih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:axe-battle" {...props}></Icon>
<style>
:global(.vop1yybih) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 6.5l-8.5-3Q2 9.25 3.5 15l8.5-3l8.5 3q1.5-5.75 0-11.5ZM12 3v18.5");
}

</style>
