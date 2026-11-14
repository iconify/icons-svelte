<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g9msq0hph"/><path class="ab-94pb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:hangar" {...props}></Icon>
<style>
:global(.ab-94pb1j) {
  d: path("M6.5 20.5v-8h11v8");
}

:global(.g9msq0hph) {
  d: path("M2.5 20.5V11a9.5 8 0 0 1 19 0v9.5Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
