<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co3_zcc8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:climb-instruction" {...props}></Icon>
<style>
:global(.co3_zcc8i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 21V3.5M3.5 8L8 3.5L12.5 8M17 3.5V21m0-13h3m-3 5h3m-3 5h3");
}

</style>
