<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d44arq5fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-reply-20-regular" {...props}></Icon>
<style>
:global(.d44arq5fj) {
  fill: currentColor;
  d: path("M7.354 3.646a.5.5 0 0 1 0 .708L3.707 8H10.5a7.5 7.5 0 0 1 7.5 7.5a.5.5 0 0 1-1 0A6.5 6.5 0 0 0 10.5 9H3.707l3.647 3.646a.5.5 0 0 1-.708.708l-4.5-4.5a.5.5 0 0 1 0-.708l4.5-4.5a.5.5 0 0 1 .708 0");
}

</style>
