<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mosi2bbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:git-commit-light" {...props}></Icon>
<style>
:global(.mosi2bbui) {
  fill: currentColor;
  d: path("M248 122h-66.34a54 54 0 0 0-107.32 0H8a6 6 0 0 0 0 12h66.34a54 54 0 0 0 107.32 0H248a6 6 0 0 0 0-12m-120 48a42 42 0 1 1 42-42a42 42 0 0 1-42 42");
}

</style>
