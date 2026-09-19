<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iplx3sbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:haixueacademy" {...props}></Icon>
<style>
:global(.iplx3sbcu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.25 36.666l14.625-25.331L43.5 36.665H24L14.25 19.78L4.5 36.666z");
}

</style>
