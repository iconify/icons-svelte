<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hveos1a4i"/><path class="fey2-dbyt"/><path class="f3a-c11xy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:energy-refund" {...props}></Icon>
<style>
:global(.f3a-c11xy) {
  d: path("m12.75 9.25l-2.5 3h3.5l-2.5 3");
}

:global(.fey2-dbyt) {
  d: path("m6.75 6.5l-3 .75l-.75-3M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

:global(.hveos1a4i) {
  d: path("M3.75 7.25a9.5 9.5 0 1 1 0 9.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
