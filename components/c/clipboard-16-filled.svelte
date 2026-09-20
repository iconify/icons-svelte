<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="i116fsfby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:clipboard-16-filled" {...props}></Icon>
<style>
:global(.i116fsfby) {
  fill: currentColor;
  d: path("M5.085 2A1.5 1.5 0 0 1 6.5 1h3a1.5 1.5 0 0 1 1.415 1h.585A1.5 1.5 0 0 1 13 3.5v10a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 13.5v-10A1.5 1.5 0 0 1 4.5 2zM6.5 2a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1z");
}

</style>
