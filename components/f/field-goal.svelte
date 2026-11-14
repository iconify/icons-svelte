<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="h1fafmbqp"/><path class="vksq-bbsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:field-goal" {...props}></Icon>
<style>
:global(.h1fafmbqp) {
  d: path("M5 2.5v9h14v-9m-7 9v10");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.vksq-bbsl) {
  d: path("M8.5 6a3.5 2.25 0 1 0 7 0a3.5 2.25 0 1 0-7 0Z");
}

</style>
