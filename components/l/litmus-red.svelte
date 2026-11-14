<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e8tw6fbis"/><path class="ya6sr4buk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:litmus-red" {...props}></Icon>
<style>
:global(.e8tw6fbis) {
  d: path("M3.5 12h2v7A2.5 2.5 0 0 0 8 21.5h8a2.5 2.5 0 0 0 2.5-2.5v-7h2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ya6sr4buk) {
  fill: currentColor;
  d: path("m13.058 2.401l3.913.832l-3.223 15.161l-3.912-.832Z");
}

</style>
