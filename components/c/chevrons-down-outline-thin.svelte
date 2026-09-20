<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kw9oa7xce"/><path class="cdily2n9h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:chevrons-down-outline-thin" {...props}></Icon>
<style>
:global(.cdily2n9h) {
  d: path("m4 13 8 8 8 -8");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.kw9oa7xce) {
  d: path("m4 4 8 8 8 -8");
}

</style>
