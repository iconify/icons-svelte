<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ogotumxvb"/><path class="opf9-sbyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:auto-start-stop" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ogotumxvb) {
  d: path("M17.303 6.697A7.5 7.5 0 1 1 12 4.5");
}

:global(.opf9-sbyl) {
  d: path("M10.25 2.75L12 4.5l-1.75 1.75m4.225 4.025a3.5 3.5 0 1 1-4.95 0M12 8.75v4");
}

</style>
