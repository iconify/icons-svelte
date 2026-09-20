<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="pjaiepbgj"><g transform="translate(-2 .955)scale(3.9999)" class="hwneuincd"><rect class="iaivzbq-f"/><rect class="wandjd64r"/><rect class="pkylttd2t"/><rect class="m9e9rob-w"/></g><path class="n7xp5lbtn"/><path class="dm9xkhblt"/><path class="bttmy5xjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vscode-icons:file-type-sitemap" {...props}></Icon>
<style>
:global(.bttmy5xjf) {
  d: path("M25 15.85h2v5.52h-2z");
}

:global(.dm9xkhblt) {
  d: path("M27 15.067v2H4.995v-2z");
}

:global(.hwneuincd) {
  stroke: var(--svg-color--f16427, #f16427);
  stroke-width: var(--svg-stroke-width--0-234px, 0.234px);
}

:global(.iaivzbq-f) {
  width: 1.766px;
  height: 1.766px;
  x: 1.117px;
  y: 5.117px;
  rx: 0.442px;
  ry: 0.442px;
}

:global(.m9e9rob-w) {
  width: 1.766px;
  height: 1.766px;
  x: 6.117px;
  y: 5.117px;
  rx: 0.442px;
  ry: 0.442px;
}

:global(.n7xp5lbtn) {
  d: path("M15 10.367h2v11.395h-2zM5 15.339h2v5.96H5z");
}

:global(.pjaiepbgj) {
  fill: var(--svg-color--f16427, #f16427);
}

:global(.pkylttd2t) {
  width: 1.766px;
  height: 1.766px;
  x: 3.617px;
  y: 5.117px;
  rx: 0.442px;
  ry: 0.442px;
}

:global(.wandjd64r) {
  width: 1.766px;
  height: 1.766px;
  x: 3.617px;
  y: 0.639px;
  rx: 0.442px;
  ry: 0.442px;
}

</style>
