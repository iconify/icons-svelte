<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y-4f_6b9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:comma-20-regular" {...props}></Icon>
<style>
:global(.y-4f_6b9d) {
  fill: currentColor;
  d: path("M13.5 7.5a3.5 3.5 0 1 0-1.28 2.707c-.262 1.167-.693 2.133-1.236 2.881C10.071 14.348 8.84 15 7.5 15a.5.5 0 0 0 0 1c1.698 0 3.217-.839 4.294-2.325C12.866 12.197 13.5 10.086 13.5 7.5");
}

</style>
