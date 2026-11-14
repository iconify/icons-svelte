<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7qukr6-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:expand-all" {...props}></Icon>
<style>
:global(.v7qukr6-v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 12h17M12 9V3.5m-4.5 4L12 3l4.5 4.5M12 15v5.5m-4.5-4L12 21l4.5-4.5");
}

</style>
