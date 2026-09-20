<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ppw67dbax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-left-20-regular" {...props}></Icon>
<style>
:global(.ppw67dbax) {
  fill: currentColor;
  d: path("M9.159 16.867a.5.5 0 1 0 .674-.739l-6.168-5.63h13.831a.5.5 0 0 0 0-1H3.668l6.165-5.629a.5.5 0 0 0-.674-.738L2.243 9.445a.75.75 0 0 0-.24.631a.75.75 0 0 0 .24.477z");
}

</style>
