<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hber9tbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:bookmark-32-regular" {...props}></Icon>
<style>
:global(.hber9tbtk) {
  fill: currentColor;
  d: path("M6 7.2A4.2 4.2 0 0 1 10.2 3h11.6A4.2 4.2 0 0 1 26 7.2V28a1 1 0 0 1-1.585.81L16 22.735L7.585 28.81A1 1 0 0 1 6 28zM10.2 5A2.2 2.2 0 0 0 8 7.2v18.844l7.415-5.355a1 1 0 0 1 1.17 0L24 26.044V7.2A2.2 2.2 0 0 0 21.8 5z");
}

</style>
