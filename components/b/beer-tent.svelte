<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eif318bhe"/><path class="v8i71dbdt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:beer-tent" {...props}></Icon>
<style>
:global(.eif318bhe) {
  d: path("M12.25 17H2.5L10 2.5l5.042 9.748");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.v8i71dbdt) {
  d: path("m7.5 17l2.5-5l2.24 4.481M15 15h4.5v5a1.5 1.5 0 0 1-1.5 1.5h-1.5A1.5 1.5 0 0 1 15 20Zm4.5 1h.5a1.5 1.5 0 0 1 0 3h-.5");
}

</style>
