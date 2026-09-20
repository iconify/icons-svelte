<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ucw6zypdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-left-32-filled" {...props}></Icon>
<style>
:global(.ucw6zypdp) {
  fill: currentColor;
  d: path("M20.884 5.366a1.25 1.25 0 0 1 0 1.768L12.018 16l8.866 8.866a1.25 1.25 0 0 1-1.768 1.768l-9.75-9.75a1.25 1.25 0 0 1 0-1.768l9.75-9.75a1.25 1.25 0 0 1 1.768 0");
}

</style>
