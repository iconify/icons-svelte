<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xzyapnbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:line-horizontal-4-48-filled" {...props}></Icon>
<style>
:global(.xzyapnbjx) {
  fill: currentColor;
  d: path("M42.5 38a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3zm0-10a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3zm0-10a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3zm0-10a1.5 1.5 0 0 1 0 3h-37a1.5 1.5 0 0 1 0-3z");
}

</style>
