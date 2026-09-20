<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="g02pdcsyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-up-12-filled" {...props}></Icon>
<style>
:global(.g02pdcsyx) {
  fill: currentColor;
  d: path("M3.076 7.383A1 1 0 0 0 4 8h4a1 1 0 0 0 .707-1.707l-2-2a1 1 0 0 0-1.414 0l-2 2a1 1 0 0 0-.217 1.09");
}

</style>
