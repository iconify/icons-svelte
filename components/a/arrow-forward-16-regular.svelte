<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j3j51ikwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-forward-16-regular" {...props}></Icon>
<style>
:global(.j3j51ikwi) {
  fill: currentColor;
  d: path("M9.646 3.646a.5.5 0 0 0 0 .708L12.293 7H7.5A5.5 5.5 0 0 0 2 12.5a.5.5 0 0 0 1 0A4.5 4.5 0 0 1 7.5 8h4.793l-2.647 2.646a.5.5 0 0 0 .708.708l3.5-3.5a.5.5 0 0 0 0-.708l-3.5-3.5a.5.5 0 0 0-.708 0");
}

</style>
