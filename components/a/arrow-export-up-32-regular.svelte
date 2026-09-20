<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="emumfacig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-export-up-32-regular" {...props}></Icon>
<style>
:global(.emumfacig) {
  fill: currentColor;
  d: path("M26 28a1 1 0 1 1 0 2H6a1 1 0 0 1 0-2zM15.293 2.293a1 1 0 0 1 1.414 0l7.5 7.5a1 1 0 1 1-1.414 1.414L17 5.414V24a1 1 0 1 1-2 0V5.414l-5.793 5.793a1 1 0 1 1-1.414-1.414z");
}

</style>
