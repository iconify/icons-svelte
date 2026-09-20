<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="jqzkbwbya"/><path class="wc2iww91l"/><path class="uwclokbjs"/><path class="uyr1302ms"/><path class="tit913_ho"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="h5uycs4sy"/><path class="wp75hkmty"/><path class="y2lgilb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rate-limit-duotone-bold" {...props}></Icon>
<style>
:global(.h5uycs4sy) {
  d: path("M2 16h8");
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.jqzkbwbya) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.o0-3vqblf) {
  d: path("M2 8h8");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

:global(.tit913_ho) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M13 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uwclokbjs) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 16h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.uyr1302ms) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wc2iww91l) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.wp75hkmty) {
  d: path("M11 7v10");
}

:global(.y2lgilb0y) {
  d: path("M13 12h9");
}

</style>
