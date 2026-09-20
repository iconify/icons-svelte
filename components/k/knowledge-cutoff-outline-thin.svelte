<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g-pndgz7k"/><path class="y_uork5-p"/><path class="me2guebva"/><path class="pkr04599e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:knowledge-cutoff-outline-thin" {...props}></Icon>
<style>
:global(.g-pndgz7k) {
  d: path("M2 12h10");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.me2guebva) {
  d: path("m18 9.5 3 3");
}

:global(.pkr04599e) {
  d: path("m21 9.5 -3 3");
}

:global(.y_uork5-p) {
  d: path("M15 7v10");
}

</style>
