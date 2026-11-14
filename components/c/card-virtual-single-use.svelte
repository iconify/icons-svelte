<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p4h-4p6kc"/><path class="yjgya_t8z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:card-virtual-single-use" {...props}></Icon>
<style>
:global(.p4h-4p6kc) {
  d: path("M15.2 19H2.5V5h19v14h-.2M2.5 9.5h18.1m-18.1 0h18.1M6 15h2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yjgya_t8z) {
  d: path("M16.75 16.5L18.5 15v6");
}

</style>
