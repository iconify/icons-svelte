<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wl3n3ac2c"/><circle class="xp85f9bzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-account-balance-wallet" {...props}></Icon>
<style>
:global(.wl3n3ac2c) {
  fill: currentColor;
  d: path("M21 7.28V5c0-1.1-.9-2-2-2H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2v-2.28A2 2 0 0 0 22 15V9a2 2 0 0 0-1-1.72M20 9v6h-7V9zM5 19V5h14v2h-6c-1.1 0-2 .9-2 2v6c0 1.1.9 2 2 2h6v2z");
}

:global(.xp85f9bzt) {
  cx: 16px;
  cy: 12px;
  r: 1.5px;
  fill: currentColor;
}

</style>
