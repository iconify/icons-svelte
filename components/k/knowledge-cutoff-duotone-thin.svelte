<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cup1acuxo"/><path class="c8lxf1b3v"/><path class="jcb5sjbcz"/><path class="asg48chvp"/><path class="g-pndgz7k"/><path class="y_uork5-p"/><path class="me2guebva"/><path class="pkr04599e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:knowledge-cutoff-duotone-thin" {...props}></Icon>
<style>
:global(.asg48chvp) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m21 9.5 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.c8lxf1b3v) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 7v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.cup1acuxo) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

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

:global(.jcb5sjbcz) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m18 9.5 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
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
