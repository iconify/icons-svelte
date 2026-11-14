<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="q5tlj4lac"/><path class="fgbh5-b-q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:contract-add" {...props}></Icon>
<style>
:global(.fgbh5-b-q) {
  d: path("M8 16.5c1-3.5 2.75-3.5 2.75-1c0 1.487.691 1.592 1.456.932M18 15v6m-3-3h6");
}

:global(.q5tlj4lac) {
  d: path("M12.178 20.5H5v-18h8.5L19 8v4.222M13.5 2.5V8H19M8 7.5h3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
