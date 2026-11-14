<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uljtwvzxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:national-government" {...props}></Icon>
<style>
:global(.uljtwvzxk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 20.5h19M3 12.5h18m-14.5 0v8m5.5-8v8m5.5-8v8M7 12.5a5 5 0 0 1 10 0m-5-5V3");
}

</style>
