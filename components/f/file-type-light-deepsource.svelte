<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m-2xz_bjl"/><path class="bn4lhe5vb"/><path class="fqq84qbqj"/><path class="dom6b4yjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-light-deepsource" {...props}></Icon>
<style>
:global(.bn4lhe5vb) {
  fill: var(--svg-color--33cb9a, #33cb9a);
  d: path("M8.86 7.6h9.21c.78 0 1.43.76 1.43 1.68s-.65 1.68-1.43 1.68H8.86z");
}

:global(.dom6b4yjl) {
  fill: var(--svg-color--f3cb51, #f3cb51);
  d: path("M8.86 14.32h5.95c.73 0 1.33.76 1.33 1.68s-.6 1.68-1.33 1.68H8.86z");
}

:global(.fqq84qbqj) {
  fill: var(--svg-color--d22f43, #d22f43);
  d: path("M8.86 21.04H19.8c.75 0 1.38.76 1.38 1.68s-.63 1.68-1.38 1.68H8.86z");
}

:global(.m-2xz_bjl) {
  fill: var(--svg-color--121317, #121317);
  d: path("M4.1 2v28H13q4.6 0 7.94-1.8a13 13 0 0 0 5.15-4.93q1.8-3.16 1.81-7.27c.01-4.11-.6-5.16-1.81-7.27s-2.93-3.76-5.15-4.93A16.5 16.5 0 0 0 13 2z");
}

</style>
