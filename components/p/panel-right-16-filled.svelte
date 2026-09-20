<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="t-2zz6ecl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-right-16-filled" {...props}></Icon>
<style>
:global(.t-2zz6ecl) {
  fill: currentColor;
  d: path("M11.5 3A2.5 2.5 0 0 1 14 5.5v5a2.5 2.5 0 0 1-2.5 2.5h-7A2.5 2.5 0 0 1 2 10.5v-5A2.5 2.5 0 0 1 4.5 3zM9 4H4.5A1.5 1.5 0 0 0 3 5.5v5A1.5 1.5 0 0 0 4.5 12H9z");
}

</style>
