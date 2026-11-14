<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="oeucrxbku"/><path class="l-9k33bgn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:form-checklist" {...props}></Icon>
<style>
:global(.l-9k33bgn) {
  d: path("m6.75 7l1.5 1.5l2.75-3m-4.25 6.75l1.5 1.5l2.75-3M7 15.5h3.5V19H7ZM13.5 7H17m-3.5 5.25H17m-3.5 5H17");
}

:global(.oeucrxbku) {
  d: path("M3.5 2.5h17v19h-17Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
