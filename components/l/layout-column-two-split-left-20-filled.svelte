<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dlsi9bb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:layout-column-two-split-left-20-filled" {...props}></Icon>
<style>
:global(.dlsi9bb-o) {
  fill: currentColor;
  d: path("M14 17h-3.5V3H14a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3M6 3h3.5v6.5H3V6a3 3 0 0 1 3-3m-3 7.5V14a3 3 0 0 0 3 3h3.5v-6.5z");
}

</style>
