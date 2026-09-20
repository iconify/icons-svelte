<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vlx079bdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-upload-32-regular" {...props}></Icon>
<style>
:global(.vlx079bdg) {
  fill: currentColor;
  d: path("M7 2a1 1 0 0 0 0 2h18a1 1 0 1 0 0-2zm9.707 4.293a1 1 0 0 0-1.414 0l-7 7a1 1 0 1 0 1.414 1.414L15 9.414V29a1 1 0 1 0 2 0V9.414l5.293 5.293a1 1 0 0 0 1.414-1.414z");
}

</style>
