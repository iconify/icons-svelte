<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sfzm4zcuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-down-16-regular" {...props}></Icon>
<style>
:global(.sfzm4zcuz) {
  fill: currentColor;
  d: path("M3.146 5.646a.5.5 0 0 1 .708 0L8 9.793l4.146-4.147a.5.5 0 0 1 .708.708l-4.5 4.5a.5.5 0 0 1-.708 0l-4.5-4.5a.5.5 0 0 1 0-.708");
}

</style>
