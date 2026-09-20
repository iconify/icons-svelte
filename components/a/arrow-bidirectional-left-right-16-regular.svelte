<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t6t1wwzmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-bidirectional-left-right-16-regular" {...props}></Icon>
<style>
:global(.t6t1wwzmi) {
  fill: currentColor;
  d: path("M2.146 8.853a.5.5 0 0 1 0-.707l3-3a.5.5 0 1 1 .708.707L3.707 8h8.586l-2.147-2.147a.5.5 0 0 1 .708-.707l3 3a.5.5 0 0 1 0 .707l-3 3a.5.5 0 0 1-.708-.707L12.293 9H3.707l2.147 2.146a.5.5 0 1 1-.708.707z");
}

</style>
