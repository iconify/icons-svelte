<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xqn9q_xyw"/><path class="m90ufg8yb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:bank-kiosk" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.m90ufg8yb) {
  d: path("M9.618 7.125a2.75 2.75 0 0 1 4.764 0");
}

:global(.xqn9q_xyw) {
  d: path("M5.623 3h12.754a1.75 1.75 0 0 1 1.718 2.084l-1.07 5.5A1.75 1.75 0 0 1 17.308 12H6.692a1.75 1.75 0 0 1-1.717-1.416l-1.07-5.5A1.75 1.75 0 0 1 5.623 3M10 12v7m4-7v7m-6.75 0h9.5A1.25 1.25 0 0 1 18 20.25a1.25 1.25 0 0 1-1.25 1.25h-9.5A1.25 1.25 0 0 1 6 20.25A1.25 1.25 0 0 1 7.25 19M12 8.5h.01");
}

</style>
