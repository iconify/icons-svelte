<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="jppo72b_l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:radiation" {...props}></Icon>
<style>
:global(.jppo72b_l) {
  d: path("M15 17.25a6 6 0 0 1-6 0l1.5-2.75a3 3 0 0 0 3 0Zm0-10.5A6 6 0 0 1 18 12h-3a3 3 0 0 0-1.5-2.5ZM6 12a6 6 0 0 1 3-5.25l1.5 2.75A3 3 0 0 0 9 12Zm6 0h.01");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
