<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ocl4q-d-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:cosmopolitan" {...props}></Icon>
<style>
:global(.ocl4q-d-n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 6h16l-8 8Zm8 8v7m-4 0h8M7 9h10m-3.5-3a3.5 3.5 0 0 1 7 0");
}

</style>
