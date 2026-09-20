<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qn154jb7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:dialpad-32-filled" {...props}></Icon>
<style>
:global(.qn154jb7b) {
  fill: currentColor;
  d: path("M9 7.5a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m7-14a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m7-21a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5m0 7a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

</style>
