<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hki91i-sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dismiss-32-regular" {...props}></Icon>
<style>
:global(.hki91i-sd) {
  fill: currentColor;
  d: path("M26.29 4.293a1 1 0 1 1 1.414 1.414L17.413 16l10.291 10.29a1 1 0 1 1-1.414 1.414L16 17.413L5.707 27.704a1 1 0 0 1-1.414-1.414L14.585 16L4.293 5.707a1 1 0 0 1 1.414-1.414L16 14.584z");
}

</style>
