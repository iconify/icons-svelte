<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wnruagb8u"/><path class="unxm2cc_a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:esim-download" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.unxm2cc_a) {
  d: path("M10.25 14.5h3.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-3.5a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75m1.75-9v6M9.5 9l2.5 2.5L14.5 9");
}

:global(.wnruagb8u) {
  d: path("M4.5 4.5a2 2 0 0 1 2-2H14L19.5 8v11.5a2 2 0 0 1-2 2h-11a2 2 0 0 1-2-2Z");
}

</style>
