<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wd7-_jags"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:move-selection-up-outline" {...props}></Icon>
<style>
:global(.wd7-_jags) {
  fill: currentColor;
  d: path("M6 14V2h12v12zm2-2h8V4H8zm8 6v-2h2v2zM6 18v-2h2v2zm10 4v-2h2v2zm-5 0v-2h2v2zm-5 0v-2h2v2zm6-14");
}

</style>
