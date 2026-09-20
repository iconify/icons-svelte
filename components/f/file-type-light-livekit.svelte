<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="gwocms_dw"/><path class="k-afuabcu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-light-livekit" {...props}></Icon>
<style>
:global(.ft5dv1b6b) {
  fill: none;
}

:global(.gwocms_dw) {
  fill: var(--svg-color--002cf2, #002cf2);
  d: path("M18.8 13.2h-5.6v5.6h5.6zm5.6-5.6h-5.6v5.6h5.6zm0 11.2h-5.6v5.6h5.6zM30 2h-5.6v5.6H30Zm0 22.4h-5.6V30H30Z");
}

:global(.k-afuabcu) {
  fill: var(--svg-color--000, #000);
  d: path("M7.6 24.4V2H2v28h16.8v-5.6h-5.6Z");
}

</style>
