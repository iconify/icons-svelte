<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rwno-zber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:artboard-portrait" {...props}></Icon>
<style>
:global(.rwno-zber) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.625 5.25h6.75A2.625 2.625 0 0 1 18 7.875v10.75a2.625 2.625 0 0 1-2.625 2.625h-6.75A2.625 2.625 0 0 1 6 18.625V7.875A2.625 2.625 0 0 1 8.625 5.25M6 2.5h5");
}

</style>
