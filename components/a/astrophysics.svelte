<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t9ctlnboy"/><path class="zyvvwvutj"/><path class="jim3asmme"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:astrophysics" {...props}></Icon>
<style>
:global(.jim3asmme) {
  d: path("M12 9.5q.5 2 2.5 2.5q-2 .5-2.5 2.5q-.5-2-2.5-2.5q2-.5 2.5-2.5Z");
}

:global(.t9ctlnboy) {
  d: path("M4 4a11.31 4 45 0 0 16 16A11.31 4 45 0 0 4 4Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zyvvwvutj) {
  d: path("M20 4A11.31 4-45 0 0 4 20A11.31 4-45 0 0 20 4Z");
}

</style>
