<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="ssvg-id-light-skin-tonea" x1="64" x2="64" y1="4.5" y2="123.82" gradientUnits="userSpaceOnUse"><stop offset="0" class="k-3zj920p"/><stop offset=".37" class="uz0bzy8lt"/><stop offset=".684" class="j5du6ed1o"/><stop offset=".976" class="pp1hlp-4g"/><stop offset="1" class="mvow2-bee"/></linearGradient><path fill="url(#ssvg-id-light-skin-tonea)" class="bwf9m2bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noto:light-skin-tone" {...props}></Icon>
<style>
:global(.bwf9m2bjt) {
  d: path("M4 4h120v120H4z");
}

:global(.j5du6ed1o) {
  stop-color: var(--svg-color--fcd8af, #FCD8AF);
}

:global(.k-3zj920p) {
  stop-color: var(--svg-color--f9ddbd, #F9DDBD);
}

:global(.mvow2-bee) {
  stop-color: var(--svg-color--ffd29c, #FFD29C);
}

:global(.pp1hlp-4g) {
  stop-color: var(--svg-color--ffd39e, #FFD39E);
}

:global(.uz0bzy8lt) {
  stop-color: var(--svg-color--fadcba, #FADCBA);
}

</style>
