<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zxkau9bfm"/><path class="fsw6zwgdz"/><path class="jqgsitb_l"/><path class="jmyx7l3yg"/><path class="ij8iy1bmr"/><path class="zf1w7lv3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-elm" {...props}></Icon>
<style>
:global(.fsw6zwgdz) {
  fill: var(--svg-color--eea400, #eea400);
  d: path("m24.13 23.362l5.87 5.87v-11.74Z");
}

:global(.ij8iy1bmr) {
  fill: var(--svg-color--8cd636, #8cd636);
  d: path("m23.392 9.376l6.594 6.594l-6.624 6.624L16.768 16ZM2.768 2l6.095 6.1h13.248L16.016 2Z");
}

:global(.jmyx7l3yg) {
  fill: var(--svg-color--5fb4cb, #5fb4cb);
  d: path("M30 14.448V2H17.552Z");
}

:global(.jqgsitb_l) {
  fill: var(--svg-color--596277, #596277);
  d: path("M15.232 16L2 2.768v26.464Z");
}

:global(.zf1w7lv3x) {
  fill: var(--svg-color--eea400, #eea400);
  d: path("m16 15.232l6.051-6.051H9.949Z");
}

:global(.zxkau9bfm) {
  fill: var(--svg-color--5fb4cb, #5fb4cb);
  d: path("M16 16.768L2.768 30h26.464Z");
}

</style>
