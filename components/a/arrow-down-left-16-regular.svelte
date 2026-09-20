<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h9l-xcbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-left-16-regular" {...props}></Icon>
<style>
:global(.h9l-xcbwg) {
  fill: currentColor;
  d: path("M8.5 13a.5.5 0 0 1 0 1h-6a.5.5 0 0 1-.5-.5v-6a.5.5 0 0 1 1 0v4.793L13.147 2.146a.5.5 0 1 1 .707.708L3.707 13z");
}

</style>
