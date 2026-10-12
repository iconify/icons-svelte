<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="dpg0g_owe"/><path class="pz576pbbr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:hours-24-sharp" {...props}></Icon>
<style>
:global(.dpg0g_owe) {
  d: path("M3.75 12a8.25 8.25 0 0 1 14.08-5.83l2.42 2.08");
}

:global(.pz576pbbr) {
  d: path("M20.25 3.75v4.5h-4.5m-10.5 6.5a2.5 2.5 0 0 1 5 0c0 2.25-5 3.25-5 6h5m7.5 0v-8.5l-5 5.75h6.5");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
