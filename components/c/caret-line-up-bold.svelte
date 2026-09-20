<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tuglxrb1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-line-up-bold" {...props}></Icon>
<style>
:global(.tuglxrb1c) {
  fill: currentColor;
  d: path("M216.49 183.51a12 12 0 0 1-17 17L128 129l-71.51 71.49a12 12 0 0 1-17-17l80-80a12 12 0 0 1 17 0ZM48 84h160a12 12 0 0 0 0-24H48a12 12 0 0 0 0 24");
}

</style>
