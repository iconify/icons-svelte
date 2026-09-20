<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o8cmwubqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-down-right-32-regular" {...props}></Icon>
<style>
:global(.o8cmwubqa) {
  fill: currentColor;
  d: path("M15 28.996a1 1 0 1 1 0-2h10.585L3.297 4.707A1 1 0 0 1 4.71 3.293L27 25.582V14.996a1 1 0 1 1 2 0v13a1 1 0 0 1-1 1z");
}

</style>
