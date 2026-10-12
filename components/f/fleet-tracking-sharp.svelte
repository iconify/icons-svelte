<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x-5qa5lrc"/><path class="klrsj1bkw"/><path class="yn4_ltk5o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:fleet-tracking-sharp" {...props}></Icon>
<style>
:global(.klrsj1bkw) {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.75h.01");
}

:global(.ux2u0rbkq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

:global(.x-5qa5lrc) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a5 5 0 0 1 5 5c0 4.5-5 8.5-5 8.5s-5-4-5-8.5a5 5 0 0 1 5-5Z");
}

:global(.yn4_ltk5o) {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 12.25h2v2c0 2.61-2 4.75-2 4.75s-2-2.14-2-4.75v-2zm14.5 0h2v2c0 2.61-2 4.75-2 4.75s-2-2.14-2-4.75v-2zm-16.5 9h18.5");
}

</style>
