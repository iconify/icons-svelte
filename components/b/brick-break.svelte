<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j6mh-y6ky"/><path class="odoruzb7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:brick-break" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.j6mh-y6ky) {
  d: path("M3 3.5h15V9h3v5.5h-3V20H3v-5.5h3V9H3ZM6 9h12M6 14.5h12");
}

:global(.odoruzb7a) {
  d: path("m9 3.5l2.5 3L10 9");
}

</style>
