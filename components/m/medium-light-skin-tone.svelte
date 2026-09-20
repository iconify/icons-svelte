<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="ssvg-id-medium-light-skin-tonea" x1="64" x2="64" y1="5" y2="123.6" gradientUnits="userSpaceOnUse"><stop offset="0" class="pm4x5bypi"/><stop offset=".411" class="vy2y4pgqt"/><stop offset=".743" class="gijgxevhi"/><stop offset="1" class="dejgk6m5t"/></linearGradient><path fill="url(#ssvg-id-medium-light-skin-tonea)" class="bwf9m2bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto:medium-light-skin-tone" {...props}></Icon>
<style>
:global(.bwf9m2bjt) {
  d: path("M4 4h120v120H4z");
}

:global(.dejgk6m5t) {
  stop-color: var(--svg-color--cca47a, #CCA47A);
}

:global(.gijgxevhi) {
  stop-color: var(--svg-color--d6b088, #D6B088);
}

:global(.pm4x5bypi) {
  stop-color: var(--svg-color--e0bb95, #E0BB95);
}

:global(.vy2y4pgqt) {
  stop-color: var(--svg-color--deb892, #DEB892);
}

</style>
