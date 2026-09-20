<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g81e20bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:hive" {...props}></Icon>
<style>
:global(.g81e20bcj) {
  fill: currentColor;
  d: path("m16.275 11.5l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3zm-5.95 3.5l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3zm0-7l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3zm-5.95 3.5l-1.7-3l1.7-3h3.35l1.625 3l-1.625 3zm0 7l-1.7-3l1.7-3h3.35l1.625 3l-1.625 3zm6.05 3.5l-1.8-3l1.7-3h3.35l1.7 3l-1.7 3zm5.85-3.5l-1.7-3l1.7-3h3.35l1.7 3l-1.7 3z");
}

</style>
