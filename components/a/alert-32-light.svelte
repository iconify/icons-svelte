<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z-ildjbqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:alert-32-light" {...props}></Icon>
<style>
:global(.z-ildjbqb) {
  fill: currentColor;
  d: path("M16 4a9 9 0 0 0-9 9v4.804l-1.93 4.825A1 1 0 0 0 5.998 24H12a4 4 0 0 0 8 0h6.002a1 1 0 0 0 .928-1.371L25 17.804V13a9 9 0 0 0-9-9m3 20a3 3 0 1 1-6 0zM8 13a8 8 0 0 1 16 0v4.804a1 1 0 0 0 .071.371L26.001 23H5.998l1.93-4.825A1 1 0 0 0 8 17.804z");
}

</style>
