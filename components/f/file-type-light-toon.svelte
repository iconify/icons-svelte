<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="pcpd3lbsk"><path class="sqzvkep3g"/><path class="kouv-mz8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-light-toon" {...props}></Icon>
<style>
:global(.kouv-mz8z) {
  fill: none;
  d: path("M8 14V4H2h12m14 18v8m-8 0V20h6");
}

:global(.pcpd3lbsk) {
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--4px, 4px);
}

:global(.sqzvkep3g) {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 4v8h8V4zM4 20v8h8v-8z");
}

</style>
