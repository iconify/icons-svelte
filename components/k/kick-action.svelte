<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uf9bxzbvl"/><path class="jdacldbtr"/><path class="qh7nafbhj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:kick-action" {...props}></Icon>
<style>
:global(.jdacldbtr) {
  d: path("M12 16a5 5 0 1 0 10 0a5 5 0 1 0-10 0Z");
}

:global(.qh7nafbhj) {
  d: path("m17 14l2 1.5l-.75 2h-2.5l-.75-2Z");
}

:global(.uf9bxzbvl) {
  d: path("M3 3.5L7.5 15q1 3.5 4.5 3.5h.75M7.5 2.5l3 9q.5 2 2 2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
