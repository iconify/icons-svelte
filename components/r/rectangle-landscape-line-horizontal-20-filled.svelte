<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ckdc98bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-landscape-line-horizontal-20-filled" {...props}></Icon>
<style>
:global(.ckdc98bjz) {
  fill: currentColor;
  d: path("M16 4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2zM5.5 7a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1z");
}

</style>
