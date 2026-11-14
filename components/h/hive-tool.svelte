<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c8beolbrg"/><path class="hyk-8yb9a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:hive-tool" {...props}></Icon>
<style>
:global(.c8beolbrg) {
  d: path("M17.127 7.227L4.399 19.955l-.708-3.536L15.005 5.106");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hyk-8yb9a) {
  d: path("M15.005 5.106a3 3 0 0 1 4.243 4.242");
}

</style>
