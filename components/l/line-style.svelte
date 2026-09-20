<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iduv_-qnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:line-style" {...props}></Icon>
<style>
:global(.iduv_-qnu) {
  fill: currentColor;
  d: path("M3 20v-2h2v2zm0-4v-2h5v2zm0-4v-2h8v2zm0-4V4h18v4zm4 12v-2h2v2zm2.5-4v-2h5v2zm1.5 4v-2h2v2zm2-8v-2h8v2zm2 8v-2h2v2zm1-4v-2h5v2zm3 4v-2h2v2z");
}

</style>
