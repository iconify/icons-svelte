<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="agjpipp_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dimmer-slider" {...props}></Icon>
<style>
:global(.agjpipp_g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 5.25a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m0 9h5a2 2 0 0 1 2 2a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2a2 2 0 0 1 2-2M12 10.5v3.75m0 4v3.25M4.5 5.25h2.25m10.5 0h2.25");
}

</style>
