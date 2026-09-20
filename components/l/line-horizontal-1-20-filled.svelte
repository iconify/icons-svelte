<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j_1ausbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-20-filled" {...props}></Icon>
<style>
:global(.j_1ausbav) {
  fill: currentColor;
  d: path("M2 9.75A.75.75 0 0 1 2.75 9h14.5a.75.75 0 0 1 0 1.5H2.75A.75.75 0 0 1 2 9.75");
}

</style>
