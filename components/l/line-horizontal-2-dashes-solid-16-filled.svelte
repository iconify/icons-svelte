<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n_c4z7bkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-2-dashes-solid-16-filled" {...props}></Icon>
<style>
:global(.n_c4z7bkj) {
  fill: currentColor;
  d: path("M2.75 5a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zm4.5 0a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zm4.5 0a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zm-9 5a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5z");
}

</style>
