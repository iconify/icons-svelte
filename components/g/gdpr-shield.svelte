<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dvbfptbsw"/><path class="apfkhpber"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:gdpr-shield" {...props}></Icon>
<style>
:global(.apfkhpber) {
  d: path("M9 11h6v5H9Zm1.25 0V9.5a1.75 1.75 0 0 1 3.5 0V11");
}

:global(.dvbfptbsw) {
  d: path("m12 2.5l7.5 3V11c0 5-3.25 8.5-7.5 10.5c-4.25-2-7.5-5.5-7.5-10.5V5.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
