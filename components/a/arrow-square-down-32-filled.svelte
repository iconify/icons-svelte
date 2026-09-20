<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iih-aacul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-square-down-32-filled" {...props}></Icon>
<style>
:global(.iih-aacul) {
  fill: currentColor;
  d: path("M7.5 3A4.5 4.5 0 0 0 3 7.5v17A4.5 4.5 0 0 0 7.5 29h17a4.5 4.5 0 0 0 4.5-4.5v-17A4.5 4.5 0 0 0 24.5 3zm13.793 12.293a1 1 0 0 1 1.414 1.414l-6 6a1 1 0 0 1-1.414 0l-6-6a1 1 0 1 1 1.414-1.414L15 19.586V10a1 1 0 1 1 2 0v9.586z");
}

</style>
