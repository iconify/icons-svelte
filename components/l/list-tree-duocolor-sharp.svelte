<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bbo2q_xwn"/><path class="auf36vbch"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:list-tree-duocolor-sharp" {...props}></Icon>
<style>
:global(.auf36vbch) {
  d: path("M8 6h12m-8 6h8m-8 6h8");
}

:global(.bbo2q_xwn) {
  stroke-opacity: 0.4;
  d: path("M4 6v12h4m-4-6h4");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
