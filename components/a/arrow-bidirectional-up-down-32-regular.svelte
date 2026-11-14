<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jdyoozd_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-bidirectional-up-down-32-regular" {...props}></Icon>
<style>
:global(.jdyoozd_h) {
  fill: currentColor;
  d: path("M15.293 3.293a1 1 0 0 1 1.414 0l7 7a1 1 0 1 1-1.414 1.414L17 6.414v19.172l5.293-5.293a1 1 0 0 1 1.414 1.414l-7 7a1 1 0 0 1-1.414 0l-7-7a1 1 0 1 1 1.414-1.414L15 25.586V6.414l-5.293 5.293a1 1 0 1 1-1.414-1.414z");
}

</style>
