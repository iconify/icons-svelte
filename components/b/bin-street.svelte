<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hp5vhbcxw"/><path class="t8urg_78n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:bin-street" {...props}></Icon>
<style>
:global(.hp5vhbcxw) {
  d: path("M4.5 7.5h15C19.5 4 15.5 3 12 3S4.5 4 4.5 7.5Zm2 0v11h11v-11m-9 11v3h7v-3");
}

:global(.t8urg_78n) {
  d: path("M10 12.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
