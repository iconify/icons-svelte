<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p-5_bdchz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:remote-16-regular" {...props}></Icon>
<style>
:global(.p-5_bdchz) {
  fill: currentColor;
  d: path("M13.854 2.854a.5.5 0 0 0-.708-.708l-4.5 4.5a.5.5 0 0 0 0 .708l4.5 4.5a.5.5 0 0 0 .708-.708L9.707 7zm-11 1.292a.5.5 0 1 0-.708.708L6.293 9l-4.147 4.146a.5.5 0 0 0 .708.708l4.5-4.5a.5.5 0 0 0 0-.708z");
}

</style>
