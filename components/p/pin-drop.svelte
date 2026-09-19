<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfdum9bqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:pin-drop" {...props}></Icon>
<style>
:global(.jfdum9bqs) {
  fill: currentColor;
  d: path("M18 8c0-3.31-2.69-6-6-6S6 4.69 6 8c0 4.5 6 11 6 11s6-6.5 6-11m-8 0c0-1.1.9-2 2-2s2 .9 2 2a2 2 0 1 1-4 0M5 20v2h14v-2z");
}

</style>
