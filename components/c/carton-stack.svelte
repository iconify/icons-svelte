<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fjhkdyb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:carton-stack" {...props}></Icon>
<style>
:global(.fjhkdyb_f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13.5h5.5A1.5 1.5 0 0 1 12 15v4a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 19v-4A1.5 1.5 0 0 1 5 13.5m8.5 0H19a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-5.5A1.5 1.5 0 0 1 12 19v-4a1.5 1.5 0 0 1 1.5-1.5M9.25 6h5.5a1.5 1.5 0 0 1 1.5 1.5v4a1.5 1.5 0 0 1-1.5 1.5h-5.5a1.5 1.5 0 0 1-1.5-1.5v-4A1.5 1.5 0 0 1 9.25 6M6 13.5v3");
}

</style>
