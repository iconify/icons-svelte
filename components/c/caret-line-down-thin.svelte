<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="tgp-tubdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:caret-line-down-thin" {...props}></Icon>
<style>
:global(.tgp-tubdy) {
  fill: currentColor;
  d: path("M45.17 74.83a4 4 0 0 1 5.66-5.66L128 146.34l77.17-77.17a4 4 0 1 1 5.66 5.66l-80 80a4 4 0 0 1-5.66 0ZM208 188H48a4 4 0 0 0 0 8h160a4 4 0 0 0 0-8");
}

</style>
