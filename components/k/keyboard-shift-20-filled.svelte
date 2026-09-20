<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k2cp3raze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:keyboard-shift-20-filled" {...props}></Icon>
<style>
:global(.k2cp3raze) {
  fill: currentColor;
  d: path("M11.139 2.528a1.492 1.492 0 0 0-2.278 0l-6.62 7.803c-.553.651-.093 1.654.759 1.654h3.01v5.012A1 1 0 0 0 7.006 18h5.986a1 1 0 0 0 .998-1.003v-5.012H17c.85 0 1.31-1.003.759-1.654z");
}

</style>
