<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kezy3sbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-up-right-32-filled" {...props}></Icon>
<style>
:global(.kezy3sbui) {
  fill: currentColor;
  d: path("M15.25 3a1.25 1.25 0 1 0 0 2.5h9.482L3.366 26.866a1.25 1.25 0 0 0 1.768 1.768L26.5 7.268v9.482a1.25 1.25 0 1 0 2.5 0V4.25C29 3.56 28.44 3 27.75 3z");
}

</style>
