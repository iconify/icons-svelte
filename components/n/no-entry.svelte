<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="tp37llbfn"/><path class="f0l74ubxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto-v1:no-entry" {...props}></Icon>
<style>
:global(.f0l74ubxj) {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M64 .57C28.96.57.57 28.97.57 64c0 35.04 28.39 63.43 63.43 63.43c35.02 0 63.43-28.4 63.43-63.43S99.02.57 64 .57M15.58 76.53V51.47h96.83v25.05H15.58z");
}

:global(.tp37llbfn) {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.58 51.47h96.83v25.05H15.58z");
}

</style>
