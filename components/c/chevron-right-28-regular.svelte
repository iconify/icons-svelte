<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="o7il89j6u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-right-28-regular" {...props}></Icon>
<style>
:global(.o7il89j6u) {
  fill: currentColor;
  d: path("M9.97 4.22a.75.75 0 0 1 1.06 0l8.75 8.75a.75.75 0 0 1 0 1.06l-8.75 8.75a.75.75 0 1 1-1.06-1.06l8.22-8.22l-8.22-8.22a.75.75 0 0 1 0-1.06");
}

</style>
