<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z77mre9ce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:daserste" {...props}></Icon>
<style>
:global(.z77mre9ce) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M39.57 5.5v29.73L19.78 42.5V21.32L8.43 25.5V17Z");
}

</style>
