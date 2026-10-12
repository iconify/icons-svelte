<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gz6olcczg"/><path class="hak_f-7gb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:dendrogram" {...props}></Icon>
<style>
:global(.gz6olcczg) {
  d: path("M4.5 20.25V15H9v5.25M6.75 15V7.75H17V12m-5.25-4.25v-4.5");
}

:global(.hak_f-7gb) {
  d: path("M14.5 20.25V12h5v8.25");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
