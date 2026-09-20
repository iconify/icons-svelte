<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="got74ghtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-portrait-48-filled" {...props}></Icon>
<style>
:global(.got74ghtl) {
  fill: currentColor;
  d: path("M14.25 44A6.25 6.25 0 0 1 8 37.75v-27.5A6.25 6.25 0 0 1 14.25 4h19.5A6.25 6.25 0 0 1 40 10.25v27.5A6.25 6.25 0 0 1 33.75 44z");
}

</style>
