<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m8g6o5bqp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:document-20-filled" {...props}></Icon>
<style>
:global(.m8g6o5bqp) {
  fill: currentColor;
  d: path("M10 2v4.5A1.5 1.5 0 0 0 11.5 8H16v8.5a1.5 1.5 0 0 1-1.5 1.5h-9A1.5 1.5 0 0 1 4 16.5v-13A1.5 1.5 0 0 1 5.5 2zm1 .25V6.5a.5.5 0 0 0 .5.5h4.25z");
}

</style>
