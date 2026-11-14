<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cm18oib_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bloody-mary" {...props}></Icon>
<style>
:global(.cm18oib_t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5 6.5l1.5 15h11l1.5-15M10 17l4.5-12m-2-2l2 2l3-1.5");
}

</style>
