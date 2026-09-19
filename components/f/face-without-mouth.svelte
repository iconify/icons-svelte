<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="djvj59_xy"/><circle class="pchx_i0bq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:face-without-mouth" {...props}></Icon>
<style>
:global(.djvj59_xy) {
  cx: 20.5px;
  cy: 28.5px;
  r: 5px;
}

:global(.fbp0m0b1e) {
  fill: var(--svg-color--664e27, #664e27);
}

:global(.pchx_i0bq) {
  cx: 43.5px;
  cy: 28.5px;
  r: 5px;
}

:global(.rhvdvboaq) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

</style>
