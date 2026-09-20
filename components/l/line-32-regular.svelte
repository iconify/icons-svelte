<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ypkukuijd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-32-regular" {...props}></Icon>
<style>
:global(.ypkukuijd) {
  fill: currentColor;
  d: path("M28.707 3.293a1 1 0 0 1 0 1.414l-24 24a1 1 0 0 1-1.414-1.414l24-24a1 1 0 0 1 1.414 0");
}

</style>
