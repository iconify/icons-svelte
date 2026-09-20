<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="se9d1pb0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-step-in-right-20-regular" {...props}></Icon>
<style>
:global(.se9d1pb0w) {
  fill: currentColor;
  d: path("M15 10a1 1 0 1 0 2 0a1 1 0 0 0-2 0m1 2a2 2 0 1 1 0-4a2 2 0 0 1 0 4M2 10a.5.5 0 0 1 .5-.5h7.793L7.146 6.354a.5.5 0 1 1 .708-.708l4 4a.5.5 0 0 1 0 .708l-4 4a.5.5 0 0 1-.708-.708l3.147-3.146H2.5A.5.5 0 0 1 2 10");
}

</style>
