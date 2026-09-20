<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xtyi2l_ww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-12-regular" {...props}></Icon>
<style>
:global(.xtyi2l_ww) {
  fill: currentColor;
  d: path("M7.354 2.146a.5.5 0 0 1 0 .708L4.207 6l3.147 3.146a.5.5 0 1 1-.708.708l-3.5-3.5a.5.5 0 0 1 0-.708l3.5-3.5a.5.5 0 0 1 .708 0");
}

</style>
