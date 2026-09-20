<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m4s6987eb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-reply-down-20-regular" {...props}></Icon>
<style>
:global(.m4s6987eb) {
  fill: currentColor;
  d: path("M17.5 4a.5.5 0 0 1 .5.5a7.5 7.5 0 0 1-7.5 7.5H3.707l3.647 3.646a.5.5 0 0 1-.708.708l-4.5-4.5a.5.5 0 0 1 0-.708l4.5-4.5a.5.5 0 1 1 .708.708L3.707 11H10.5A6.5 6.5 0 0 0 17 4.5a.5.5 0 0 1 .5-.5");
}

</style>
