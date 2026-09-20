<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ah5k37b7w"/><path class="asd1gsbjs"/><path class="yq5i_4bbc"/><path class="c587bq8qn"/><path class="g2oubdb_i"/><path class="o0-3vqblf"/><path class="jcxg2bbvb"/><path class="h5uycs4sy"/><path class="wp75hkmty"/><path class="y2lgilb0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:rate-limit-duotone-regular" {...props}></Icon>
<style>
:global(.ah5k37b7w) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 8h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.asd1gsbjs) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c587bq8qn) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M11 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.g2oubdb_i) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M13 12h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h5uycs4sy) {
  d: path("M2 16h8");
}

:global(.jcxg2bbvb) {
  d: path("M2 12h8");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.o0-3vqblf) {
  d: path("M2 8h8");
}

:global(.wp75hkmty) {
  d: path("M11 7v10");
}

:global(.y2lgilb0y) {
  d: path("M13 12h9");
}

:global(.yq5i_4bbc) {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
