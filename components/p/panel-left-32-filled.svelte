<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jk07_zqin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:panel-left-32-filled" {...props}></Icon>
<style>
:global(.jk07_zqin) {
  fill: currentColor;
  d: path("M25.5 28a4.5 4.5 0 0 0 4.5-4.5v-15A4.5 4.5 0 0 0 25.5 4h-19A4.5 4.5 0 0 0 2 8.5v15A4.5 4.5 0 0 0 6.5 28zm0-22A2.5 2.5 0 0 1 28 8.5v15a2.5 2.5 0 0 1-2.5 2.5H12V6z");
}

</style>
