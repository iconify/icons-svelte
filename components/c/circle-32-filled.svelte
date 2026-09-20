<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ucv4meu1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:circle-32-filled" {...props}></Icon>
<style>
:global(.ucv4meu1t) {
  fill: currentColor;
  d: path("M16 2C8.268 2 2 8.268 2 16s6.268 14 14 14s14-6.268 14-14S23.732 2 16 2");
}

</style>
