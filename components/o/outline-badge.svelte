<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-ng9spqw"/><path class="j9yiayb3m"/><circle class="v_314wjfb"/><path class="ii-sdiz7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:outline-badge" {...props}></Icon>
<style>
:global(.d-ng9spqw) {
  fill: currentColor;
  d: path("M14 12h4v1.5h-4zm0 3h4v1.5h-4z");
}

:global(.ii-sdiz7j) {
  fill: currentColor;
  d: path("M11.08 16.18c-.64-.28-1.34-.43-2.08-.43s-1.44.15-2.08.43c-.56.24-.92.78-.92 1.39V18h6v-.43c0-.61-.36-1.15-.92-1.39");
}

:global(.j9yiayb3m) {
  fill: currentColor;
  d: path("M20 7h-5V4c0-1.1-.9-2-2-2h-2c-1.1 0-2 .9-2 2v3H4c-1.1 0-2 .9-2 2v11c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V9c0-1.1-.9-2-2-2m-9 0V4h2v5h-2zm9 13H4V9h5c0 1.1.9 2 2 2h2c1.1 0 2-.9 2-2h5z");
}

:global(.v_314wjfb) {
  cx: 9px;
  cy: 13.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
