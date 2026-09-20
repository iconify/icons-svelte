<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<ellipse class="ydyu7b0ro"/><circle class="vsjgcxtmh"/><g class="yxh5jgofy"><path class="bhf3vbcol"/><path class="x3fvoacqh"/><path class="fv5q5ib5m"/><path class="nwd0n-bqf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-juice" {...props}></Icon>
<style>
:global(.bhf3vbcol) {
  d: path("M15.587 29.235h1.006V2.945h-1.006z");
}

:global(.fv5q5ib5m) {
  d: path("m7.155 6.436l-.711.71l18.581 18.599l.712-.711z");
}

:global(.nwd0n-bqf) {
  d: path("m25.75 7.161l-.71-.712L6.428 25.02l.71.711z");
}

:global(.vsjgcxtmh) {
  cx: 16.018px;
  cy: 16.018px;
  r: 13.516px;
  fill: none;
  stroke: var(--svg-color--ffc108, #ffc108);
  stroke-width: var(--svg-stroke-width--0-976px, 0.976px);
}

:global(.x3fvoacqh) {
  d: path("M2.945 15.585v1.006l26.29.005V15.59z");
}

:global(.ydyu7b0ro) {
  cx: 16px;
  cy: 16.054px;
  fill: var(--svg-color--fce494, #fce494);
  rx: 13.163px;
  ry: 13.109px;
}

:global(.yxh5jgofy) {
  fill: var(--svg-color--ffc108, #ffc108);
}

</style>
