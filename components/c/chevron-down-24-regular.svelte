<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfzl2pbug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-down-24-regular" {...props}></Icon>
<style>
:global(.hfzl2pbug) {
  fill: currentColor;
  d: path("M4.22 8.47a.75.75 0 0 1 1.06 0L12 15.19l6.72-6.72a.75.75 0 1 1 1.06 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L4.22 9.53a.75.75 0 0 1 0-1.06");
}

</style>
