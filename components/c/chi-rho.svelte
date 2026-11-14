<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li9nl1d2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chi-rho" {...props}></Icon>
<style>
:global(.li9nl1d2w) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19m0-19h2a3.5 3.5 0 0 1 0 7h-2M7.75 12l8.5 8.5m0-8.5l-8.5 8.5");
}

</style>
