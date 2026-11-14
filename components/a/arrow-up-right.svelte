<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qkit2qg8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrow-up-right" {...props}></Icon>
<style>
:global(.qkit2qg8y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 18.5l13-13m-10 0h10v10");
}

</style>
