<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="orpwl-qit"/><path class="x8eqacbvm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:civic-tech" {...props}></Icon>
<style>
:global(.orpwl-qit) {
  d: path("M13.1 15.5H4.5v-11h15v8.3m-17 5.7h9.2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.x8eqacbvm) {
  d: path("m10 8l-2 2l2 2m4-4l2 2l-2 2m.5 6l3.25-3L21 18v3.5h-6.5Z");
}

</style>
