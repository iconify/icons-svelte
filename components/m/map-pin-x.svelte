<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ci-la_tkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-pin-x" {...props}></Icon>
<style>
:global(.ci-la_tkx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21.5S4.5 15 4.5 9.5a7.5 7.5 0 0 1 15 0c0 5.5-7.5 12-7.5 12m-2-14l4 4m0-4l-4 4");
}

</style>
