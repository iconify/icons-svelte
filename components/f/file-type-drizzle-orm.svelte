<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g transform="matrix(.22192 .12396 -.12639 .22055 -4.336 -3.57)" class="m00li1bzt"><rect class="nt-s71b2m"/><rect class="x6l90cc0p"/><rect class="wj3cn1bex"/><rect class="l0cuq3bsv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-drizzle-orm" {...props}></Icon>
<style>
:global(.l0cuq3bsv) {
  width: 9.631px;
  height: 40.852px;
  x: 115.859px;
  y: 12.451px;
  rx: 4.816px;
}

:global(.m00li1bzt) {
  fill: var(--svg-color--c5f74f, #c5f74f);
}

:global(.nt-s71b2m) {
  width: 9.631px;
  height: 40.852px;
  x: 71.193px;
  y: 37.556px;
  rx: 4.816px;
}

:global(.wj3cn1bex) {
  width: 9.631px;
  height: 40.852px;
  x: 134.57px;
  y: -22.003px;
  rx: 4.816px;
}

:global(.x6l90cc0p) {
  width: 9.631px;
  height: 40.852px;
  x: 89.898px;
  y: 3.105px;
  rx: 4.816px;
}

</style>
