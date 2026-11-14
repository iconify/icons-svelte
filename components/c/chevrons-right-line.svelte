<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euky03sgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:chevrons-right-line" {...props}></Icon>
<style>
:global(.euky03sgk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.5 5v14m-9-12.5L16 12l-5.5 5.5m-6-11L10 12l-5.5 5.5");
}

</style>
