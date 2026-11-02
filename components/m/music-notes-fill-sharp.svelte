<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nwa_l136f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-notes-fill-sharp" {...props}></Icon>
<style>
:global(.nwa_l136f) {
  fill: currentColor;
  d: path("M8 7a1 1 0 0 1 .684-.949l12-4A1.002 1.002 0 0 1 22 3v13a4.001 4.001 0 1 1-2-3.465V4.387L10 7.721V18a4.001 4.001 0 1 1-2-3.465Z");
}

</style>
