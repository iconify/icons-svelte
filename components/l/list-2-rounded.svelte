<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2cj-py_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:list-2-rounded" {...props}></Icon>
<style>
:global(.k2cj-py_n) {
  fill: currentColor;
  d: path("M8 18q-.425 0-.712-.288T7 17t.288-.712T8 16h8q.425 0 .713.288T17 17t-.288.713T16 18zm-4-5q-.425 0-.712-.288T3 12t.288-.712T4 11h16q.425 0 .713.288T21 12t-.288.713T20 13zm4-5q-.425 0-.712-.288T7 7t.288-.712T8 6h8q.425 0 .713.288T17 7t-.288.713T16 8z");
}

</style>
