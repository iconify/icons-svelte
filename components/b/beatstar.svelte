<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ioewulbpj"/><path class="kkcmfab9h"/></g><path class="c0wwv4bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:beatstar" {...props}></Icon>
<style>
:global(.c0wwv4bkg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 30.373h39v3.259h-39z");
}

:global(.ioewulbpj) {
  d: path("M11.117 16.149H8.749L4.5 30.373h39l-4.249-14.224h-2.368");
}

:global(.kkcmfab9h) {
  d: path("M38.765 25.041v2.744H9.235v-2.744l2.367-10.673h24.796zM11 25.389h26");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
