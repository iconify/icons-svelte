<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="osyjl-b8a"/><path class="m4gbe7uux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:novolumeslider" {...props}></Icon>
<style>
:global(.m4gbe7uux) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 41.938c9.907 0 17.938-8.031 17.938-17.938S15.407 6.062 5.5 6.062z");
}

:global(.osyjl-b8a) {
  cx: 34.084px;
  cy: 15.133px;
  r: 8.416px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
