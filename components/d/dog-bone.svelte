<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gcyxu3b2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:dog-bone" {...props}></Icon>
<style>
:global(.gcyxu3b2c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10.25H7A2.25 2.25 0 1 0 4.5 12A2.25 2.25 0 1 0 7 13.75h5m0-3.5h5A2.25 2.25 0 1 1 19.5 12a2.25 2.25 0 1 1-2.5 1.75h-5");
}

</style>
