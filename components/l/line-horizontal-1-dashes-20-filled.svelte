<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jekll6byt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-1-dashes-20-filled" {...props}></Icon>
<style>
:global(.jekll6byt) {
  fill: currentColor;
  d: path("M2 9.75A.75.75 0 0 1 2.75 9h2.5a.75.75 0 0 1 0 1.5h-2.5A.75.75 0 0 1 2 9.75m6 0A.75.75 0 0 1 8.75 9h2.5a.75.75 0 0 1 0 1.5h-2.5A.75.75 0 0 1 8 9.75m6 0a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75");
}

</style>
