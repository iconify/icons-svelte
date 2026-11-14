<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4ebob_a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:accelerator" {...props}></Icon>
<style>
:global(.qk4ebob_a) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 19.25a9 9 0 1 1 12.5 0M12 13l5-5m-5 5h.01");
}

</style>
