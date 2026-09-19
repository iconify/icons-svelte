<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n3nrthbmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:pizzahut" {...props}></Icon>
<style>
:global(.n3nrthbmp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 29.95l-10.02-6.91l-1.77-4.99H16.29l-1.77 4.99L4.5 29.95z");
}

</style>
