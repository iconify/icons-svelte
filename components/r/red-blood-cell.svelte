<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p24jq9byl"/><path class="omt08ib-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:red-blood-cell" {...props}></Icon>
<style>
:global(.omt08ib-v) {
  d: path("M7.5 11a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0ZM5 15.5c2 1.75 4.5 2.5 7 2.5");
}

:global(.p24jq9byl) {
  d: path("M2.5 12a9.5 6.75 0 1 0 19 0a9.5 6.75 0 1 0-19 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
