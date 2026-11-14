<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t1i_qqbnx"/><path class="bm7drqnbo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:pallet-jack" {...props}></Icon>
<style>
:global(.bm7drqnbo) {
  d: path("M6 20a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6.5-6.5h9m-8.5 0V18m4-4.5V18m4-4.5V18");
}

:global(.t1i_qqbnx) {
  d: path("M8 9v9h13.5M8 9L4 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
