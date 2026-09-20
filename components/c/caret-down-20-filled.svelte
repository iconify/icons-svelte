<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jzryuftlr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-down-20-filled" {...props}></Icon>
<style>
:global(.jzryuftlr) {
  fill: currentColor;
  d: path("M5.797 7a1 1 0 0 0-.778 1.628l3.814 4.723a1.5 1.5 0 0 0 2.334 0l3.815-4.723A1 1 0 0 0 14.204 7z");
}

</style>
