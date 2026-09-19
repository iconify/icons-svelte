<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vcis5xbns"/><path class="i30ec3bzu"/><path class="ox-eaybnt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:blade-player" {...props}></Icon>
<style>
:global(.i30ec3bzu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.004 23.462l-3.312 1.91l-3.311 1.91V19.64l3.311 1.91Zm1.958 13.506V23.46a10.332 10.332 0 1 1 5.627 9.128V42.5Z");
}

:global(.ox-eaybnt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.466 23.46l-3.311-1.91l-3.312-1.91v7.64l3.312-1.91Z");
}

:global(.vcis5xbns) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.958 17.269a10.21 10.21 0 0 0-12.831-2.937v-3.206L5.5 5.5v17.96a10.27 10.27 0 0 0 16.474 8.177");
}

</style>
