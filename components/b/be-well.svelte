<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="iv2vw8q-z"/><path class="l9hmjgifv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:be-well" {...props}></Icon>
<style>
:global(.iv2vw8q-z) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.5 26.692c0-7.18 5.82-13 13-13s13 5.82 13 13s-5.82 13-13 13h-13z");
}

:global(.l9hmjgifv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.308 30.5c-5.077-5.077-5.077-13.308 0-18.385c5.076-5.076 13.308-5.076 18.384 0c5.077 5.077 5.077 13.308 0 18.385L17.5 39.692z");
}

</style>
