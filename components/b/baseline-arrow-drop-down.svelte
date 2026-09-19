<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ep6q_wb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-arrow-drop-down" {...props}></Icon>
<style>
:global(.ep6q_wb2x) {
  fill: currentColor;
  d: path("m7 10l5 5l5-5z");
}

</style>
