<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjws-xr1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:outdoor-siren" {...props}></Icon>
<style>
:global(.gjws-xr1m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17v-4a5 5 0 0 1 10 0v4M4.5 17h15v4h-15ZM12 2.5V5M4 6l1.75 1.75M20 6l-1.75 1.75");
}

</style>
