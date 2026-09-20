<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ppf2z0bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:app-recent-20-filled" {...props}></Icon>
<style>
:global(.ppf2z0bsr) {
  fill: currentColor;
  d: path("M7 2a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zM2 6a2 2 0 0 1 2-2v12a2 2 0 0 1-2-2zm14 10V4a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2");
}

</style>
