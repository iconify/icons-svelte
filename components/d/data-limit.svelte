<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="odyp19b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:data-limit" {...props}></Icon>
<style>
:global(.odyp19b8x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 5.5h18m-18 15h18m-14 0V14m5 6.5V10m5 10.5v-15");
}

</style>
