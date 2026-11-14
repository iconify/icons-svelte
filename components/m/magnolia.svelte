<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ong-okbak"/><path class="r9hwqz4ot"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:magnolia" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ong-okbak) {
  d: path("M12 18C8.5 15 8.5 5.5 12 3.5c3.5 2 3.5 11.5 0 14.5");
}

:global(.r9hwqz4ot) {
  d: path("M10.75 16.25C6 17 3 13 3.5 8.5c3 0 5 .75 6 2m3.75 5.75C18 17 21 13 20.5 8.5c-3 0-5 .75-6 2M12 18v3.5");
}

</style>
