<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="q-gnribuz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-step-in-diagonal-down-left-28-regular" {...props}></Icon>
<style>
:global(.q-gnribuz) {
  fill: currentColor;
  d: path("M23.78 5.28a.75.75 0 0 0-1.06-1.06l-9.22 9.22V7.75a.75.75 0 0 0-1.5 0v7.5c0 .414.336.75.75.75h7.5a.75.75 0 0 0 0-1.5h-5.69zM8 24a4 4 0 1 0 0-8a4 4 0 0 0 0 8m0-1.5a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5");
}

</style>
