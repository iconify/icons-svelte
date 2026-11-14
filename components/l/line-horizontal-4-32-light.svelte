<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fjtjqhb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-4-32-light" {...props}></Icon>
<style>
:global(.fjtjqhb_b) {
  fill: currentColor;
  d: path("M29.5 26a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-27a.5.5 0 0 1 0-1z");
}

</style>
