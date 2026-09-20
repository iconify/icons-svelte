<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rdorxcbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:point-scan-20-filled" {...props}></Icon>
<style>
:global(.rdorxcbnm) {
  fill: currentColor;
  d: path("M9 2.5a.5.5 0 0 0-1 0v4.025A5 5 0 0 0 3.525 11H8V6.525a5 5 0 0 1 1 0zM2.5 11h1.025a5 5 0 0 0 0 1H2.5a.5.5 0 0 1 0-1M8 17.5v-1.025a5 5 0 0 0 1 0V17.5a.5.5 0 0 1-1 0m5.476-5.5H17.5a.5.5 0 0 0 0-1h-4.025a5 5 0 0 1 0 1H9v4.475A5 5 0 0 0 13.476 12M8 16.475A5 5 0 0 1 3.525 12H8zM9 11h4.475A5 5 0 0 0 9 6.525z");
}

</style>
