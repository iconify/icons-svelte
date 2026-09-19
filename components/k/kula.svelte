<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ptstqk4jf"/><path class="m9jy7hbfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:kula" {...props}></Icon>
<style>
:global(.m9jy7hbfp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.345 13.28s.39 1.897 2.3 1.436c1.667-.402-3.162 14.544-1.15 18.797M26.61 14.141s2.13 2.184 5.348 3.277M28.74 24.03c-.46 1.321-1.496 3.515-2.243 3.74s-2.874-1.959-.46-4.374s12.243-2.069 2.155 11.325");
}

:global(.ptstqk4jf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 9.5v29c0 2.208-1.792 4-4 4h-29c-2.208 0-4-1.792-4-4v-29c0-2.208 1.792-4 4-4h29c2.208 0 4 1.792 4 4");
}

</style>
