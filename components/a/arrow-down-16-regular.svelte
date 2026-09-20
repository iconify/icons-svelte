<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oc5_2n-hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-16-regular" {...props}></Icon>
<style>
:global(.oc5_2n-hr) {
  fill: currentColor;
  d: path("M8.5 2.5a.5.5 0 1 0-1 0v9.697L3.872 8.166a.5.5 0 1 0-.744.668l4.5 5a.5.5 0 0 0 .744 0l4.5-5a.5.5 0 0 0-.744-.668L8.5 12.197z");
}

</style>
