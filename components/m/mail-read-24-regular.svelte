<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="glavkacrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:mail-read-24-regular" {...props}></Icon>
<style>
:global(.glavkacrv) {
  fill: currentColor;
  d: path("M13.19 2.34a2.25 2.25 0 0 0-2.38 0L3.06 7.172A2.25 2.25 0 0 0 2 9.083v7.667A3.25 3.25 0 0 0 5.25 20h13.5A3.25 3.25 0 0 0 22 16.75V9.082c0-.776-.4-1.498-1.06-1.909zm-1.587 1.272a.75.75 0 0 1 .794 0l7.242 4.517L12 12.15L4.361 8.13zM3.5 9.371l8.15 4.29a.75.75 0 0 0 .7 0l8.15-4.29v7.379a1.75 1.75 0 0 1-1.75 1.75H5.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
