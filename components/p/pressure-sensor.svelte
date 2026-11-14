<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2be_4bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:pressure-sensor" {...props}></Icon>
<style>
:global(.i2be_4bgq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 7.5a5 5 0 1 0 10 0a5 5 0 1 0-10 0m5 5v3m-9.5 0h19m-19 5h19M12 7.5l2.25-2.25");
}

</style>
