<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="zef_6xa6v"/><g class="dt4yhf73z"><circle class="qkqe84bny"/><circle class="bdxd6db2u"/><circle class="r5fl0lb3y"/><circle class="bkx_pysua"/><circle class="l-elexbss"/><circle class="ho4lh1bfe"/><circle class="of3reof2o"/><circle class="g5q-qcc2j"/><circle class="ynx9hebhd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:full-moon" {...props}></Icon>
<style>
:global(.bdxd6db2u) {
  cx: 20px;
  cy: 17px;
  r: 3px;
}

:global(.bkx_pysua) {
  cx: 22px;
  cy: 5px;
  r: 2px;
}

:global(.dt4yhf73z) {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

:global(.g5q-qcc2j) {
  cx: 32px;
  cy: 19px;
  r: 2px;
}

:global(.ho4lh1bfe) {
  cx: 30px;
  cy: 9px;
  r: 1px;
}

:global(.l-elexbss) {
  cx: 3px;
  cy: 18px;
  r: 1px;
}

:global(.of3reof2o) {
  cx: 15px;
  cy: 31px;
  r: 1px;
}

:global(.qkqe84bny) {
  cx: 10.5px;
  cy: 8.5px;
  r: 3.5px;
}

:global(.r5fl0lb3y) {
  cx: 24.5px;
  cy: 28.5px;
  r: 3.5px;
}

:global(.ynx9hebhd) {
  cx: 10px;
  cy: 23px;
  r: 2px;
}

:global(.zef_6xa6v) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffd983, #ffd983);
}

</style>
