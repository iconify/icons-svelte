<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rdc56lgrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-counterclockwise-20-regular" {...props}></Icon>
<style>
:global(.rdc56lgrp) {
  fill: currentColor;
  d: path("M16 10A6 6 0 0 0 5.528 6H7.5a.5.5 0 0 1 0 1h-3a.5.5 0 0 1-.5-.5v-3a.5.5 0 0 1 1 0v1.601a7 7 0 1 1-1.98 4.361a.5.5 0 0 1 .998.076A6 6 0 1 0 16 10");
}

</style>
