<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z9wc188rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:magnustrainer" {...props}></Icon>
<style>
:global(.z9wc188rh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.17 22.84h15.66m-2.58 0h-10.5L14.62 43.5h18.76zM12.55 43.5h22.9m-22.9-3.62h22.9m-6.2-17.04l4.64-9.27a22 22 0 0 0-19.78 0l4.64 9.27ZM24 11.22V4.5m-3.36 2.93h6.72");
}

</style>
