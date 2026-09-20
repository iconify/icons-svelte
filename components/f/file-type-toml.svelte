<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g9js08b5r"/><path class="iqi33wbcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-toml" {...props}></Icon>
<style>
:global(.g9js08b5r) {
  fill: var(--svg-color--7f7f7f, #7f7f7f);
  d: path("M22.76 6.83v3.25h-5v15.09h-3.5V10.08h-5V6.83Z");
}

:global(.iqi33wbcy) {
  fill: var(--svg-color--bfbfbf, #bfbfbf);
  d: path("M2 2h6.2v3.09H5.34v21.8H8.2V30H2Zm28 28h-6.2v-3.09h2.86V5.11H23.8V2H30Z");
}

</style>
