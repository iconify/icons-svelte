<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iugemnp2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:quote-right-fill-round" {...props}></Icon>
<style>
:global(.iugemnp2s) {
  fill: currentColor;
  d: path("M9 12v-2a2 2 0 1 0-2 2Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 6 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H7a4 4 0 1 1 4-4Zm8-1v-2a2 2 0 1 0-2 2Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 16 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H17a4 4 0 1 1 4-4Z");
}

</style>
