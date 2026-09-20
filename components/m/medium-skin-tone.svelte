<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="ssvg-id-medium-skin-tonea" x1="64" x2="64" y1="3.667" y2="123.67" gradientUnits="userSpaceOnUse"><stop offset="0" class="nf0zjyg-o"/><stop offset=".449" class="trruj12ov"/><stop offset=".809" class="coz_uibmc"/><stop offset="1" class="n5m-09b7m"/></linearGradient><path fill="url(#ssvg-id-medium-skin-tonea)" class="bwf9m2bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto:medium-skin-tone" {...props}></Icon>
<style>
:global(.bwf9m2bjt) {
  d: path("M4 4h120v120H4z");
}

:global(.coz_uibmc) {
  stop-color: var(--svg-color--ad8264, #AD8264);
}

:global(.n5m-09b7m) {
  stop-color: var(--svg-color--a47b62, #A47B62);
}

:global(.nf0zjyg-o) {
  stop-color: var(--svg-color--ba8d68, #BA8D68);
}

:global(.trruj12ov) {
  stop-color: var(--svg-color--b78a67, #B78A67);
}

</style>
