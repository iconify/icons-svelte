<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbyd9acws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:fir-tree" {...props}></Icon>
<style>
:global(.jbyd9acws) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5L6.5 9H9l-4.5 5.5h3l-4 5h17l-4-5h3L15 9h2.5Zm0 17v2");
}

</style>
