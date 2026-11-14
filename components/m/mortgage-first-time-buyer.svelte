<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hzn3tmbmt"/><path class="ntbkwacax"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:mortgage-first-time-buyer" {...props}></Icon>
<style>
:global(.hzn3tmbmt) {
  d: path("M13.46 20.5H4v-10l8-7l7.503 6.565");
}

:global(.ntbkwacax) {
  d: path("M16 7V4h2v4.75m-1.75 8l2.25-2V21m-2.25 0h4.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
