<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="n9ke7c7eh"/><path class="bi-mr0blb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:habits" {...props}></Icon>
<style>
:global(.bi-mr0blb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.113 26.172l5.462 10.658l16.061-16.268");
}

:global(.n9ke7c7eh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29a4 4 0 0 1-4-4v-29a4 4 0 0 1 4-4h29a4 4 0 0 1 4 4v29a4 4 0 0 1-4 4m-33-26.925h37");
}

</style>
