<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tsofxdb6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-flow-diagonal-up-right-16-filled" {...props}></Icon>
<style>
:global(.tsofxdb6r) {
  fill: currentColor;
  d: path("M8.5 3a.5.5 0 0 0 0 1h2.793L5.879 9.414a2.5 2.5 0 1 0 .707.707L12 4.707V7.5a.5.5 0 0 0 1 0v-4a.5.5 0 0 0-.5-.5z");
}

</style>
