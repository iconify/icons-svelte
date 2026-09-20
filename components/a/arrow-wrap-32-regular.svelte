<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zrbtsibbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-wrap-32-regular" {...props}></Icon>
<style>
:global(.zrbtsibbb) {
  fill: currentColor;
  d: path("M3 7a1 1 0 0 1 1-1h19.5a5.5 5.5 0 1 1 0 11h-15a3.5 3.5 0 1 0 0 7h18.086l-1.293-1.293a1 1 0 0 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414-1.414L26.586 26H8.5a5.5 5.5 0 1 1 0-11h15a3.5 3.5 0 1 0 0-7H4a1 1 0 0 1-1-1");
}

</style>
