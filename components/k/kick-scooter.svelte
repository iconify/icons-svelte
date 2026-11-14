<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ih35gcvua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:kick-scooter" {...props}></Icon>
<style>
:global(.ih35gcvua) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m14 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m-.5-16l2.25 13.75M3.5 14H18M13.75 3h5");
}

</style>
