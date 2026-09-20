<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lnmf6ybei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:more-vertical-48-filled" {...props}></Icon>
<style>
:global(.lnmf6ybei) {
  fill: currentColor;
  d: path("M24 16a3.5 3.5 0 1 1 0-7a3.5 3.5 0 0 1 0 7m0 11.5a3.5 3.5 0 1 1 0-7a3.5 3.5 0 0 1 0 7m-3.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0");
}

</style>
