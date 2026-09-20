<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x427syy9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-circle-down-right-24-filled" {...props}></Icon>
<style>
:global(.x427syy9h) {
  fill: currentColor;
  d: path("M12 22c5.523 0 10-4.477 10-10S17.523 2 12 2S2 6.477 2 12s4.477 10 10 10m2.5-13.25a.75.75 0 0 1 1.5 0v6.5a.75.75 0 0 1-.75.75h-6.5a.75.75 0 0 1 0-1.5h4.74L8.222 9.283a.75.75 0 0 1 1.056-1.066L14.5 13.39z");
}

</style>
