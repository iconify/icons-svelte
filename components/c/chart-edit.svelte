<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fg8nb-p7y"/><path class="v0eflybks"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:chart-edit" {...props}></Icon>
<style>
:global(.fg8nb-p7y) {
  d: path("M3.5 3v17.5H12");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v0eflybks) {
  d: path("M6.5 14L10 8.5l3 2.5l6-6.5m2.5 12l-4.25 4.25l-2.5.5l.5-2.5l4.25-4.25l2 2m-6.25 2.25l2 2");
}

</style>
