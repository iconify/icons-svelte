<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rkrvudbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-48-regular" {...props}></Icon>
<style>
:global(.rkrvudbag) {
  fill: currentColor;
  d: path("M43.634 4.366a1.25 1.25 0 0 1 0 1.768l-37.5 37.5a1.25 1.25 0 0 1-1.768-1.768l37.5-37.5a1.25 1.25 0 0 1 1.768 0");
}

</style>
