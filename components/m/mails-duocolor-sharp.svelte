<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="v1yjf7bhh"/><path class="ztbg_oopf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:mails-duocolor-sharp" {...props}></Icon>
<style>
:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.v1yjf7bhh) {
  stroke-opacity: 0.4;
  d: path("M7 5V3h14v12");
}

:global(.ztbg_oopf) {
  d: path("M3 9h14v12H3Zm0 0l6 6h2l6-6");
}

</style>
