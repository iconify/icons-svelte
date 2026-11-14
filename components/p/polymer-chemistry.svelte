<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fy-ek2bhp"/><path class="rnjmlsb1m"/><path class="d0piyhban"/><path class="s2zg3jb7k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:polymer-chemistry" {...props}></Icon>
<style>
:global(.d0piyhban) {
  d: path("m9.767 15.185l5.556-8.315l2.91 1.945l-5.556 8.315Z");
}

:global(.fy-ek2bhp) {
  d: path("M1.767 15.185L7.323 6.87l2.91 1.945l-5.556 8.315Z");
}

:global(.rnjmlsb1m) {
  d: path("m8.677 6.87l5.556 8.315l-2.91 1.945l-5.556-8.315Z");
}

:global(.s2zg3jb7k) {
  d: path("m16.677 6.87l5.556 8.315l-2.91 1.945l-5.556-8.315Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
