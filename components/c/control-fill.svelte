<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cc1vfbn8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:control-fill" {...props}></Icon>
<style>
:global(.cc1vfbn8p) {
  fill: currentColor;
  d: path("M207.39 123.06A8 8 0 0 1 200 128H56a8 8 0 0 1-5.66-13.66l72-72a8 8 0 0 1 11.32 0l72 72a8 8 0 0 1 1.73 8.72");
}

</style>
