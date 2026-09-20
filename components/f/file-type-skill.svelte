<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="rlchu4bbo"><path class="m7r1gybom"/><path class="llt6oibol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-skill" {...props}></Icon>
<style>
:global(.llt6oibol) {
  stroke: var(--svg-color--000, #000);
  stroke-width: var(--svg-stroke-width--2-71px, 2.71px);
  d: path("m16 6.97l7.82 4.51v9.04L16 25.03l-7.82-4.51v-9.04z");
}

:global(.m7r1gybom) {
  d: path("m16 2l12.12 7v14L16 30L3.88 23V9z");
}

:global(.rlchu4bbo) {
  fill: var(--svg-color--dedede, #dedede);
}

</style>
