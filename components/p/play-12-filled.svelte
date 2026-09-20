<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tn8l8q8_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:play-12-filled" {...props}></Icon>
<style>
:global(.tn8l8q8_o) {
  fill: currentColor;
  d: path("M4.496 1.994A1 1 0 0 0 3 2.862v6.277a1 1 0 0 0 1.496.868l5.492-3.139a1 1 0 0 0 0-1.736z");
}

</style>
