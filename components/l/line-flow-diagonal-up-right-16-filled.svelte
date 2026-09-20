<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="rzsgbkj8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-flow-diagonal-up-right-16-filled" {...props}></Icon>
<style>
:global(.rzsgbkj8d) {
  fill: currentColor;
  d: path("M12.854 3.854a.5.5 0 0 0-.708-.708L5.88 9.414a2.5 2.5 0 1 0 .707.707z");
}

</style>
