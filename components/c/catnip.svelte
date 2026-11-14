<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ewdp8rbqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:catnip" {...props}></Icon>
<style>
:global(.ewdp8rbqp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.5v12m0-12c-3-2-2.5-5 0-7c2.5 2 3 5 0 7m0 5.5c-2.5-4-6-4.5-8.5-3.5c1.5 3.5 5 5 8.5 3.5m0 0c2.5-4 6-4.5 8.5-3.5c-1.5 3.5-5 5-8.5 3.5");
}

</style>
