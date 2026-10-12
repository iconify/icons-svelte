<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="wzp_c7b6a"/><path class="c92gv4ess"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:jharokha-sharp" {...props}></Icon>
<style>
:global(.c92gv4ess) {
  d: path("M9 16v-3.5a3 3 0 0 1 6 0V16Zm-4.75 0h15.5M7.5 16c0 3 1 5 2.5 5.25M16.5 16c0 3-1 5-2.5 5.25");
}

:global(.wzp_c7b6a) {
  d: path("M7.75 3H17l.55.51l2.65 2.48l.55.51H3.25l.55-.51l2.65-2.48L7 3zM5.5 6.5h13V16h-13z");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
