<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="or_74dohl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:device-tablet-camera-thin" {...props}></Icon>
<style>
:global(.or_74dohl) {
  fill: currentColor;
  d: path("M192 28H64a20 20 0 0 0-20 20v160a20 20 0 0 0 20 20h128a20 20 0 0 0 20-20V48a20 20 0 0 0-20-20m12 180a12 12 0 0 1-12 12H64a12 12 0 0 1-12-12V48a12 12 0 0 1 12-12h128a12 12 0 0 1 12 12ZM136 68a8 8 0 1 1-8-8a8 8 0 0 1 8 8");
}

</style>
