<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="weugfgbse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-image-left-sharp" {...props}></Icon>
<style>
:global(.weugfgbse) {
  fill: currentColor;
  d: path("M3 17V7h10v10zM3 5V3h18v2zm12 4V7h6v2zm0 4v-2h6v2zm0 4v-2h6v2zM3 21v-2h18v2z");
}

</style>
