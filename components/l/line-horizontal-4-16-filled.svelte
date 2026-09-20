<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lbjgo8bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-4-16-filled" {...props}></Icon>
<style>
:global(.lbjgo8bte) {
  fill: currentColor;
  d: path("M2.75 3a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5zm0 3a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5zM2 9.75A.75.75 0 0 1 2.75 9h10.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 9.75M2.75 12a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5z");
}

</style>
