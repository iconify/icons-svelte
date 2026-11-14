<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bs-3aibik"/><path class="myxi6ubgo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:laundry-room" {...props}></Icon>
<style>
:global(.bs-3aibik) {
  d: path("M2.5 10h19M4 10h16l-1.5 11.5h-13Zm2 0c0-3.5 3-5 6-4c2-1.5 5.5-.5 6 4");
}

:global(.myxi6ubgo) {
  d: path("M15 10h2.75l1.5 6l-2.25.5Zm-9 4h8.5m-8 3.75H15");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
