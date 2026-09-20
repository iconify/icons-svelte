<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lsfmj_w-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:minimize-24-filled" {...props}></Icon>
<style>
:global(.lsfmj_w-i) {
  fill: currentColor;
  d: path("M3.996 13H20a1 1 0 1 0 0-2H3.996a1 1 0 1 0 0 2");
}

</style>
