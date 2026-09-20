<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qx9xa_uch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:pipeline-32-regular" {...props}></Icon>
<style>
:global(.qx9xa_uch) {
  fill: currentColor;
  d: path("M2 9a3 3 0 0 1 6 0h16a3 3 0 1 1 6 0v14a3 3 0 1 1-6 0H8a3 3 0 1 1-6 0zm4 0a1 1 0 0 0-2 0v14a1 1 0 1 0 2 0zm2 12h16V11H8zM28 9a1 1 0 1 0-2 0v14a1 1 0 1 0 2 0z");
}

</style>
