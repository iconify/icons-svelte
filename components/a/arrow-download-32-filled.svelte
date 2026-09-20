<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bglwzdb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-download-32-filled" {...props}></Icon>
<style>
:global(.bglwzdb4g) {
  fill: currentColor;
  d: path("M17.25 4.25a1.25 1.25 0 1 0-2.5 0v15.482l-4.616-4.616a1.25 1.25 0 0 0-1.768 1.768l6.75 6.75a1.25 1.25 0 0 0 1.768 0l6.75-6.75a1.25 1.25 0 0 0-1.768-1.768l-4.616 4.616zm-11 22.25a1.25 1.25 0 1 0 0 2.5h19.5a1.25 1.25 0 1 0 0-2.5z");
}

</style>
