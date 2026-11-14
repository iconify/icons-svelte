<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gkw9efb7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:lane-booking" {...props}></Icon>
<style>
:global(.gkw9efb7s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4 21.5l5-19m11 19l-5-19M8.75 15a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0M12 5.5h.01");
}

</style>
