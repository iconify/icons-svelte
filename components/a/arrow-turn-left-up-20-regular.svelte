<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q6-qw0ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:arrow-turn-left-up-20-regular" {...props}></Icon>
<style>
:global(.q6-qw0ble) {
  fill: currentColor;
  d: path("M3.146 8.854a.5.5 0 0 1 0-.708l4-4a.5.5 0 0 1 .708 0l4 4a.5.5 0 0 1-.708.708L8 5.707V12a2 2 0 0 0 2 2h6.5a.5.5 0 0 1 0 1H10a3 3 0 0 1-3-3V5.707L3.854 8.854a.5.5 0 0 1-.708 0");
}

</style>
