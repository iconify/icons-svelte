<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="brj1p7r3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-portrait-32-filled" {...props}></Icon>
<style>
:global(.brj1p7r3b) {
  fill: currentColor;
  d: path("M8.5 30A4.5 4.5 0 0 1 4 25.5v-19A4.5 4.5 0 0 1 8.5 2h15A4.5 4.5 0 0 1 28 6.5v19a4.5 4.5 0 0 1-4.5 4.5z");
}

</style>
