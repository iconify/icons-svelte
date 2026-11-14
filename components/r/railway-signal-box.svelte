<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pd48vtbno"/><path class="yujqyty0g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:railway-signal-box" {...props}></Icon>
<style>
:global(.pd48vtbno) {
  d: path("M2.5 21V11l5.75-4.5L14 11v10Zm15 0V3.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.yujqyty0g) {
  d: path("M5.25 13.75h6v3.5h-6ZM17.5 6l4-2.5");
}

</style>
