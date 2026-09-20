<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vg7l92bmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:caret-up-24-filled" {...props}></Icon>
<style>
:global(.vg7l92bmx) {
  fill: currentColor;
  d: path("M6.102 16.98c-1.074 0-1.648-1.264-.94-2.073l5.521-6.31a1.75 1.75 0 0 1 2.634 0l5.522 6.31c.707.809.133 2.073-.94 2.073z");
}

</style>
