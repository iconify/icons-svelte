<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ysfxy4mei"/><path class="bifprne6g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hazard-flammable" {...props}></Icon>
<style>
:global(.bifprne6g) {
  d: path("M12 21.5c-2 0-3-1.5-3-3c0-2 2-3 3-5c1 2 3 3 3 5c0 1.5-1 3-3 3");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ysfxy4mei) {
  d: path("M12 21.5c-4.5 0-7-3-7-6.5c0-4.5 4-6.5 5-12c3.5 2 4 5 3.5 7.5c1.5-1 2-2 2.5-3c2 2 3 5 3 7.5c0 3.5-2.5 6.5-7 6.5Z");
}

</style>
