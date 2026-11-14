<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryvda3bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:outage-restored" {...props}></Icon>
<style>
:global(.ryvda3bhf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2L3.5 12.5h6l-1.5 8l8-11h-5.5Zm2.75 16l2 2L21 15.75");
}

</style>
