<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p-jlzp0rn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:previous-20-filled" {...props}></Icon>
<style>
:global(.p-jlzp0rn) {
  fill: currentColor;
  d: path("M17 4.252c0-1-1.116-1.595-1.947-1.038L6.554 8.921a1.25 1.25 0 0 0-.007 2.071l8.5 5.793A1.25 1.25 0 0 0 17 15.752zM3 3.5a.5.5 0 0 1 1 0v13a.5.5 0 0 1-1 0z");
}

</style>
