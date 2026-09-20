<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yxwv-5bfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:edit-16-filled" {...props}></Icon>
<style>
:global(.yxwv-5bfi) {
  fill: currentColor;
  d: path("M10.529 1.764a2.621 2.621 0 1 1 3.707 3.707l-.779.779L9.75 2.543zM9.043 3.25L2.657 9.636a2.96 2.96 0 0 0-.772 1.354l-.87 3.386a.5.5 0 0 0 .61.608l3.385-.869a2.95 2.95 0 0 0 1.354-.772l6.386-6.386z");
}

</style>
