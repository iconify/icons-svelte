<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vi7cghb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:minimize-48-filled" {...props}></Icon>
<style>
:global(.vi7cghb8h) {
  fill: currentColor;
  d: path("M6 23.5A1.5 1.5 0 0 1 7.5 22h33a1.5 1.5 0 0 1 0 3h-33A1.5 1.5 0 0 1 6 23.5");
}

</style>
