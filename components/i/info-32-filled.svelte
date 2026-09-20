<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="slywhzb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:info-32-filled" {...props}></Icon>
<style>
:global(.slywhzb9b) {
  fill: currentColor;
  d: path("M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2m0 11a1 1 0 0 1 1 1v9a1 1 0 1 1-2 0v-9a1 1 0 0 1 1-1m0-2a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
