<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(2 2)scale(.21212)"><rect class="e_ezxwzva"/><path class="b0acwmbzg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-kysely" {...props}></Icon>
<style>
:global(.b0acwmbzg) {
  d: path("M41.3 109V24h5.2v49.3h.6L91.9 24h7l-37 40.3L98.5 109H92L58.6 68L46.5 81.2V109z");
}

:global(.e_ezxwzva) {
  width: 128px;
  height: 128px;
  x: 2px;
  y: 2px;
  fill: var(--svg-color--fff, #fff);
  stroke: var(--svg-color--121212, #121212);
  stroke-width: var(--svg-stroke-width--4px, 4px);
  rx: 16px;
}

</style>
