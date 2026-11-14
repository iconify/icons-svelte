<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yzk77_b1u"/><path class="mslly4bki"/><path class="nqj-5nbcg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bank-hours" {...props}></Icon>
<style>
:global(.mslly4bki) {
  d: path("M7.75 14.5a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0Z");
}

:global(.nqj-5nbcg) {
  d: path("M12 12v2.5l2 1");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yzk77_b1u) {
  d: path("M3 7.5h18v14H3Zm4.5 0L12 3l4.5 4.5M12 3h.01");
}

</style>
