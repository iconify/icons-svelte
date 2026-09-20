<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fnh_fzb7o"/><path class="sw6lz3bwh"/><path class="zc7p01b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:librephotosmobile" {...props}></Icon>
<style>
:global(.fnh_fzb7o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.864 39.114l14.25-14.25a1.22 1.22 0 0 0 0-1.728l-14.25-14.25a1.22 1.22 0 0 0-1.728 0l-14.25 14.25a1.22 1.22 0 0 0 0 1.728l14.25 14.25a1.22 1.22 0 0 0 1.728 0");
}

:global(.sw6lz3bwh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.864 43.142l14.25-14.25a1.22 1.22 0 0 0 0-1.728l-14.25-14.25a1.22 1.22 0 0 0-1.728 0l-14.25 14.25a1.22 1.22 0 0 0 0 1.728l14.25 14.25a1.22 1.22 0 0 0 1.728 0");
}

:global(.zc7p01b2v) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.864 35.086l14.25-14.25a1.22 1.22 0 0 0 0-1.728l-14.25-14.25a1.22 1.22 0 0 0-1.728 0l-14.25 14.25a1.22 1.22 0 0 0 0 1.728l14.25 14.25a1.22 1.22 0 0 0 1.728 0");
}

</style>
