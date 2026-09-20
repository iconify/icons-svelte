<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dqvb3uboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-wrap-up-to-down-32-regular" {...props}></Icon>
<style>
:global(.dqvb3uboe) {
  fill: currentColor;
  d: path("M7 3a1 1 0 0 0-1 1v19.5a5.5 5.5 0 1 0 11 0v-15a3.5 3.5 0 1 1 7 0v18.086l-1.293-1.293a1 1 0 0 0-1.414 1.414l3 3a1 1 0 0 0 1.414 0l3-3a1 1 0 0 0-1.414-1.414L26 26.586V8.5a5.5 5.5 0 1 0-11 0v15a3.5 3.5 0 1 1-7 0V4a1 1 0 0 0-1-1");
}

</style>
