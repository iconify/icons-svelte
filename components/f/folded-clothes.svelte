<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rr2_eznqp"/><path class="zwjedjblj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:folded-clothes" {...props}></Icon>
<style>
:global(.rr2_eznqp) {
  d: path("M3.5 4.5h17v16h-17Zm0 6h17m-17 5h17");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zwjedjblj) {
  d: path("m9 4.5l3 3l3-3");
}

</style>
