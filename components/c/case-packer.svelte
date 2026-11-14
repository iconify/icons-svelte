<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jd3k6i3ga"/><path class="bugic2bwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:case-packer" {...props}></Icon>
<style>
:global(.bugic2bwj) {
  d: path("M9 2.5h6v7.25H9Zm0 2.75h6");
}

:global(.jd3k6i3ga) {
  d: path("M2.5 9L4 12.5v9h16v-9L21.5 9M4 12.5h16");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
