<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hukz9nbfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-image-inline-right-sharp" {...props}></Icon>
<style>
:global(.hukz9nbfr) {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm8-4V7h10v10zM3 5V3h18v2zm0 12v-2h6v2z");
}

</style>
