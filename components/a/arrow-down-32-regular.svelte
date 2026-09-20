<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lkvbfykiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-32-regular" {...props}></Icon>
<style>
:global(.lkvbfykiq) {
  fill: currentColor;
  d: path("M16 3a1 1 0 0 1 1 1v21.586l8.293-8.293a1 1 0 0 1 1.414 1.414l-10 10a1 1 0 0 1-1.414 0l-10-10a1 1 0 1 1 1.414-1.414L15 25.586V4a1 1 0 0 1 1-1");
}

</style>
