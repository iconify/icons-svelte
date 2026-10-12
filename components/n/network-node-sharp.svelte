<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="e9-7-8-2z"/><path class="n64rr10zx"/><circle class="jp31ksbuo"/><path class="q_ag9ps7p"/><circle class="lwohrubnq"/><path class="b836m9q7h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:network-node-sharp" {...props}></Icon>
<style>
:global(.b836m9q7h) {
  d: path("m8.62 14.2l-1.38.8m5.63-5.75l1.29.75l.87.5V14l-.87.5l-1.29.75l-.87.5l-.87-.5l-1.29-.75l-.87-.5v-3.5l.87-.5l1.29-.75l.87-.5z");
}

:global(.e9-7-8-2z) {
  cx: 12px;
  cy: 4.75px;
  r: 2px;
}

:global(.jp31ksbuo) {
  cx: 18.5px;
  cy: 16px;
  r: 2px;
}

:global(.lwohrubnq) {
  cx: 5.5px;
  cy: 16px;
  r: 2px;
}

:global(.n64rr10zx) {
  d: path("M12 8.35v-1.6");
}

:global(.q_ag9ps7p) {
  d: path("m15.38 14.2l1.38.8");
}

:global(.x2cwu0gfd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
