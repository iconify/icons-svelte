<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c--36ycir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:baseline-clear-all" {...props}></Icon>
<style>
:global(.c--36ycir) {
  fill: currentColor;
  d: path("M5 13h14v-2H5zm-2 4h14v-2H3zM7 7v2h14V7z");
}

</style>
