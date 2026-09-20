<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qk7kykb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-turn-right-down-20-filled" {...props}></Icon>
<style>
:global(.qk7kykb0f) {
  fill: currentColor;
  d: path("M16.78 10.72a.75.75 0 0 1 0 1.06l-4 4a.75.75 0 0 1-1.06 0l-4-4a.75.75 0 1 1 1.06-1.06l2.72 2.72V7A1.5 1.5 0 0 0 10 5.5H3.75a.75.75 0 0 1 0-1.5H10a3 3 0 0 1 3 3v6.44l2.72-2.72a.75.75 0 0 1 1.06 0");
}

</style>
