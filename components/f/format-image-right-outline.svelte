<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyndqg73e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:format-image-right-outline" {...props}></Icon>
<style>
:global(.xyndqg73e) {
  fill: currentColor;
  d: path("M11 17V7h10v10zm2-2h6V9h-6zM3 21v-2h18v2zm0-4v-2h6v2zm0-4v-2h6v2zm0-4V7h6v2zm0-4V3h18v2zm13 7");
}

</style>
