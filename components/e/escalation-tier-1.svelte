<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eypwsxb4m"/><path class="ca7ojiapc"/><path class="v6zjf47kh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:escalation-tier-1" {...props}></Icon>
<style>
:global(.ca7ojiapc) {
  fill: currentColor;
  d: path("M2.5 16.5h6v5h-6Z");
}

:global(.eypwsxb4m) {
  d: path("M8.5 21.5V12h6V7.5h6v14Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v6zjf47kh) {
  d: path("M3.5 10.5L10 4M6.5 4H10v3.5");
}

</style>
