<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="dqog1_bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-right-48-regular" {...props}></Icon>
<style>
:global(.dqog1_bnj) {
  fill: currentColor;
  d: path("M4 24c0-.69.56-1.25 1.25-1.25h32.446L24.874 10.14a1.25 1.25 0 1 1 1.752-1.782l14.988 14.738l.027.026a1.25 1.25 0 0 1 .352 1.009a1.25 1.25 0 0 1-.393.785L26.626 39.641a1.25 1.25 0 1 1-1.752-1.782l12.822-12.61H5.25A1.25 1.25 0 0 1 4 24");
}

</style>
