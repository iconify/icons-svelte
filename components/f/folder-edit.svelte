<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q3wixnhae"/><path class="jrlnbgjpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:folder-edit" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jrlnbgjpw) {
  d: path("M14.828 10.672za1 1 0 0 1 0 1.414l-3.568 3.568a1.5 1.5 0 0 1-.766.41l-.439.088a.6.6 0 0 1-.707-.707l.088-.439a1.5 1.5 0 0 1 .41-.766l3.568-3.568a1 1 0 0 1 1.414 0");
}

:global(.q3wixnhae) {
  d: path("M3 7a2 2 0 0 1 2-2h4.5l2 2H19a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2Z");
}

</style>
