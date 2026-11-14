<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wql7i9b8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:map-layer-buildings" {...props}></Icon>
<style>
:global(.wql7i9b8x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 2.5h5A1.75 1.75 0 0 1 12 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75h-5a1.75 1.75 0 0 1-1.75-1.75V4.25A1.75 1.75 0 0 1 5.25 2.5M12 9h7.5a1 1 0 0 1 1 1v11.5H12m-5.75-15h3m-3 4h3m-3 4h3m5.5-1.5h3");
}

</style>
