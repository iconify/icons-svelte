<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm9vggazo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:agility-ladder-fight" {...props}></Icon>
<style>
:global(.fm9vggazo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 21L8 3m13 18L16 3M4.25 16.5h15.5M5.5 12h13M6.75 7.5h10.5");
}

</style>
