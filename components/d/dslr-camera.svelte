<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o_tckpb1q"/><path class="hr_eltbbq"/><path class="nlu9axewj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:dslr-camera" {...props}></Icon>
<style>
:global(.hr_eltbbq) {
  d: path("M8.75 14a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

:global(.nlu9axewj) {
  d: path("M11.5 14a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm-6-4v8");
}

:global(.o_tckpb1q) {
  d: path("M4.5 7h5L11 3.5h4L16.5 7h3a2 2 0 0 1 2 2v10a2 2 0 0 1-2 2h-15a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
