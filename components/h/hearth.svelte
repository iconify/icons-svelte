<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p_qxgn_6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:hearth" {...props}></Icon>
<style>
:global(.p_qxgn_6z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.63 7.15a10.12 10.12 0 0 0-7.86 16.51h0L24 42.71l16.07-18.86l.08-.09l.08-.1h0A10.13 10.13 0 1 0 24 11.58a10.1 10.1 0 0 0-8.36-4.43Z");
}

</style>
