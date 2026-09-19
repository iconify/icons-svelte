<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="o7667tbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:eruditedictionary" {...props}></Icon>
<style>
:global(.o7667tbqe) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.807 31.025A12.903 12.903 0 1 1 36.887 24H2.522A21.483 21.483 0 1 1 5.4 34.748");
}

</style>
