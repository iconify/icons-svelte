<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyb_byx3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:align-flex-center-outline" {...props}></Icon>
<style>
:global(.dyb_byx3u) {
  fill: currentColor;
  d: path("M11 22v-8.5H3v-3h8V2h2v8.5h8v3h-8V22z");
}

</style>
