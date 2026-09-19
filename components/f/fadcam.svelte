<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e0l99lzku"/><path class="q8xpzpbtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:fadcam" {...props}></Icon>
<style>
:global(.e0l99lzku) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.403 17.298c0 6.165-4.998 11.163-11.163 11.164s-11.163-4.999-11.163-11.164S18.074 6.134 24.239 6.133s11.164 4.998 11.164 11.164zM5.5 41.867C9.414 35.344 15.933 30.413 24 30.413s14.586 4.931 18.5 11.454");
}

:global(.q8xpzpbtp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.973 15.041c-.01.948-.825 1.71-1.828 1.71c-1.002 0-1.818-.762-1.827-1.71zm4.533 0c.01.948.825 1.71 1.827 1.71s1.818-.762 1.828-1.71z");
}

</style>
