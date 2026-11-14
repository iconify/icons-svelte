<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tjoq16byh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:axis-y" {...props}></Icon>
<style>
:global(.tjoq16byh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 16V2.75m-3.5 3.5l3.5-3.5l3.5 3.5M4.5 18.5h5m5 0h5m-10 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0");
}

</style>
