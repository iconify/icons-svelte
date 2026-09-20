<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t8kimy0qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:chevron-circle-right-20-filled" {...props}></Icon>
<style>
:global(.t8kimy0qz) {
  fill: currentColor;
  d: path("M10 18a8 8 0 1 1 0-16a8 8 0 0 1 0 16m-1.854-4.854a.5.5 0 0 0 .708.708l3.5-3.5a.5.5 0 0 0 0-.708l-3.5-3.5a.5.5 0 1 0-.708.708L11.293 10z");
}

</style>
