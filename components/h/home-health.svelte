<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyiigybjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:home-health" {...props}></Icon>
<style>
:global(.kyiigybjk) {
  fill: currentColor;
  d: path("M11 16.5h2V14h2.5v-2H13V9.5h-2V12H8.5v2H11zM5 20V9.5l7-5.27l7 5.27V20z");
}

</style>
