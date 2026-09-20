<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mwbgifbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:re-order-vertical-20-filled" {...props}></Icon>
<style>
:global(.mwbgifbqf) {
  fill: currentColor;
  d: path("M7.75 17.25a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0zm3 0a.75.75 0 0 0 1.5 0V2.75a.75.75 0 0 0-1.5 0z");
}

</style>
