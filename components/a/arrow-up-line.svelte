<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2hkg2bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-up-line" {...props}></Icon>
<style>
:global(.v2hkg2bjo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5V21m-5-7.5l5-5l5 5M5 3.5h14");
}

</style>
