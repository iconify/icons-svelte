<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdq53ekru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:frying-pan" {...props}></Icon>
<style>
:global(.jdq53ekru) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0m13 0h6");
}

</style>
