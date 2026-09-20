<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vjwt6hbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:minimize-12-regular" {...props}></Icon>
<style>
:global(.vjwt6hbfj) {
  fill: currentColor;
  d: path("M2 6a.5.5 0 0 1 .5-.5h7a.5.5 0 0 1 0 1h-7A.5.5 0 0 1 2 6");
}

</style>
