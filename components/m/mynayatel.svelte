<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xt9i3951u"/><path class="edyse0l7n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:mynayatel" {...props}></Icon>
<style>
:global(.edyse0l7n) {
  d: path("M9.5 5.5h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4");
}

:global(.xt9i3951u) {
  d: path("M17.641 29.814V14.5l12.718 19v-19");
}

:global(.y9tr6bcfx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
