<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1dg7abyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:mall-fountain" {...props}></Icon>
<style>
:global(.s1dg7abyc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 17h17L19 20.5H5Zm8.5 0V9m0 0c-3 0-4.5 2-5 4m5-4c3 0 4.5 2 5 4m-5-9.5v2M8.5 6h.01m6.99 0h.01");
}

</style>
