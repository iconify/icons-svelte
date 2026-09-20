<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wf133fbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-row-three-focus-top-20-filled" {...props}></Icon>
<style>
:global(.wf133fbbj) {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm10 9H4V8h12zm0 1v1a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1z");
}

</style>
