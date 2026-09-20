<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qn_-n6k2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-right-12-regular" {...props}></Icon>
<style>
:global(.qn_-n6k2v) {
  fill: currentColor;
  d: path("M4.646 2.146a.5.5 0 0 0 0 .708L7.793 6L4.646 9.146a.5.5 0 1 0 .708.708l3.5-3.5a.5.5 0 0 0 0-.708l-3.5-3.5a.5.5 0 0 0-.708 0");
}

</style>
