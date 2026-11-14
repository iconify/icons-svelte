<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q45tak3zi"/><path class="jq2jquhqx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:form-checklist" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jq2jquhqx) {
  d: path("m6.75 7l1.5 1.5l2.75-3m-4.25 6.75l1.5 1.5l2.75-3M8.5 15.5H9a1.5 1.5 0 0 1 1.5 1.5v.5A1.5 1.5 0 0 1 9 19h-.5A1.5 1.5 0 0 1 7 17.5V17a1.5 1.5 0 0 1 1.5-1.5m5-8.5H17m-3.5 5.25H17m-3.5 5H17");
}

:global(.q45tak3zi) {
  d: path("M7.875 2.5h8.25A4.375 4.375 0 0 1 20.5 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-8.25A4.375 4.375 0 0 1 3.5 17.125V6.875A4.375 4.375 0 0 1 7.875 2.5");
}

</style>
