<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nqv1_5isg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-counterclockwise-16-regular" {...props}></Icon>
<style>
:global(.nqv1_5isg) {
  fill: currentColor;
  d: path("M13 8a5 5 0 0 0-9.001-3h2a.5.5 0 1 1 0 1H3a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 1 0v1.531a6 6 0 1 1-1.476 4.513a.5.5 0 0 1 .997-.089A5 5 0 0 0 13 8");
}

</style>
