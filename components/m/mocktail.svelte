<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k7n-sz5ny"/><path class="nq1lp59jc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mocktail" {...props}></Icon>
<style>
:global(.k7n-sz5ny) {
  d: path("M7 7h10v13q0 1.5-1.5 1.5h-7Q7 21.5 7 20Zm5.5 0a3.5 3.5 0 0 1 7 0M10 10.5l-1.5-8");
}

:global(.nq1lp59jc) {
  d: path("m10.267 13.581l4.402.936l-.936 4.402l-4.402-.936Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
