<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zdgu3ybil"/><path class="wza1g1cpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:lathe-chuck" {...props}></Icon>
<style>
:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.wza1g1cpw) {
  d: path("M10 12a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm.75-8h2.5v4.5h-2.5Zm8.803 10.917l-1.25 2.166l-3.897-2.25l1.25-2.166ZM5.697 17.083l-1.25-2.166l3.897-2.25l1.25 2.166Z");
}

:global(.zdgu3ybil) {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Z");
}

</style>
