<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="rbd0m7brg"/><circle class="zf3yz_zmn"/><path class="gsffg1l2k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:neutral-face" {...props}></Icon>
<style>
:global(.fbp0m0b1e) {
  fill: var(--svg-color--664e27, #664e27);
}

:global(.gsffg1l2k) {
  d: path("M38.9 48H25.1c-1.5 0-1.5-4 0-4h13.7c1.6 0 1.6 4 .1 4");
}

:global(.rbd0m7brg) {
  cx: 20.5px;
  cy: 27.6px;
  r: 5px;
}

:global(.rhvdvboaq) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

:global(.zf3yz_zmn) {
  cx: 43.5px;
  cy: 27.6px;
  r: 5px;
}

</style>
