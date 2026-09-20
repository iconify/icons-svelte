<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ia2fmb0_f"/><path class="ln087ybbc"/><path class="tms3vccny"/><path class="uc5n3ybcz"/><path class="imq7sxbhw"/><path class="ncntbpb7p"/><path class="e4pb6sb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-bazel-version" {...props}></Icon>
<style>
:global(.e4pb6sb3t) {
  fill: var(--svg-color--f60, #f60);
  d: path("M9 2L2 9v7l14 14l14-14V9l-7-7l-7 7z");
}

:global(.ia2fmb0_f) {
  fill: var(--svg-color--76d275, #76d275);
  d: path("m9 2l7 7l-7 7l-7-7z");
}

:global(.imq7sxbhw) {
  fill: var(--svg-color--00701a, #00701a);
  d: path("M16 23v7l-7-7v-7z");
}

:global(.ln087ybbc) {
  fill: var(--svg-color--43a047, #43a047);
  d: path("M2 9v7l7 7v-7z");
}

:global(.ncntbpb7p) {
  fill: var(--svg-color--004300, #004300);
  d: path("m16 23l7-7v7l-7 7z");
}

:global(.tms3vccny) {
  fill: var(--svg-color--76d275, #76d275);
  d: path("m23 2l7 7l-7 7l-7-7z");
}

:global(.uc5n3ybcz) {
  fill: var(--svg-color--43a047, #43a047);
  d: path("M30 9v7l-7 7v-7zM16 9l7 7l-7 7l-7-7z");
}

</style>
