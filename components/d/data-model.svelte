<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rbz1jkbxr"/><path class="n-n33r6ou"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:data-model" {...props}></Icon>
<style>
:global(.n-n33r6ou) {
  d: path("m13.5 16.75l-2.75 2l2.75 2");
}

:global(.rbz1jkbxr) {
  d: path("M2.5 2.5h8V10h-8Zm11 10h8v9h-8Zm-11-7h8m3 9.75h8M6.5 10v8.75h7");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
