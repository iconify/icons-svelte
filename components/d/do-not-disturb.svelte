<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="leebu_fth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:do-not-disturb" {...props}></Icon>
<style>
:global(.leebu_fth) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 12A6.5 6.5 0 1 1 8.5 4.25A5 5 0 0 0 16.25 12M15 18h6");
}

</style>
