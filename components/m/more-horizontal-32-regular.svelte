<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ldspctbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-horizontal-32-regular" {...props}></Icon>
<style>
:global(.ldspctbcu) {
  fill: currentColor;
  d: path("M9.5 16a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m9 0a2.5 2.5 0 1 1-5 0a2.5 2.5 0 0 1 5 0m6.5 2.5a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

</style>
