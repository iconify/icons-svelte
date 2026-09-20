<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zhj_ubbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:mail-inbox-32-filled" {...props}></Icon>
<style>
:global(.zhj_ubbrl) {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v17a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5zM7.5 5A2.5 2.5 0 0 0 5 7.5V16h7a1 1 0 0 1 1 1v1a3 3 0 1 0 6 0v-1a1 1 0 0 1 1-1h7V7.5A2.5 2.5 0 0 0 24.5 5z");
}

</style>
