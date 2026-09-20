<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ju0sk_7wf"/><path class="ziznm1ama"/><path class="mxzk029nb"/><path class="y0y0ccsoe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:affinity-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.ju0sk_7wf) {
  d: path("M2 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

:global(.mxzk029nb) {
  d: path("M12 10v4");
}

:global(.y0y0ccsoe) {
  d: path("M10 12h4");
}

:global(.ziznm1ama) {
  d: path("M14 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

</style>
