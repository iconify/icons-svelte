<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mk09fccfu"/><circle class="xzditrbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-flashlight-on" {...props}></Icon>
<style>
:global(.mk09fccfu) {
  fill: currentColor;
  d: path("M18 2H6v6l2 3v11h8V11l2-3zm-2 2v1H8V4zm-2 6.4V20h-4v-9.61l-2-3V7h8v.39z");
}

:global(.xzditrbqy) {
  cx: 12px;
  cy: 14px;
  r: 1.5px;
  fill: currentColor;
}

</style>
