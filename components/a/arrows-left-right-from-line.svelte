<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wtn8x5ggd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:arrows-left-right-from-line" {...props}></Icon>
<style>
:global(.wtn8x5ggd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 12H2.75m3-3l-3 3l3 3M15 12h6.25m-3-3l3 3l-3 3M12 4v16");
}

</style>
