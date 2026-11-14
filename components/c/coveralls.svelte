<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bx0qsgb9p"/><path class="zn8hh5egl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:coveralls" {...props}></Icon>
<style>
:global(.bx0qsgb9p) {
  d: path("m9.5 3l-4 1l-3 8.5l2.5 1L7 8v13h3.5l1.5-6.5l1.5 6.5H17V8l2 5.5l2.5-1l-3-8.5l-4-1q-2.5 2.5-5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.zn8hh5egl) {
  d: path("M9.75 7.5v4h4.5v-4Z");
}

</style>
