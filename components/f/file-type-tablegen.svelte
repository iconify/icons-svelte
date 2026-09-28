<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bkibtdb8l"/><path class="amf1c9v_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-tablegen" {...props}></Icon>
<style>
:global(.amf1c9v_t) {
  fill: var(--svg-color--f7bb07, #f7bb07);
  fill-rule: evenodd;
  d: path("M17 5h4c6 0 9 4 9 11s-3 11-9 11h-4zm5 5v12c2.2-.2 3-2.4 3-6s-.8-5.8-3-6");
}

:global(.bkibtdb8l) {
  fill: var(--svg-color--984c93, #984c93);
  d: path("M2 5h13v5h-4v17H6V10H2z");
}

</style>
