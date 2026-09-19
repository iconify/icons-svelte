<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qp2wneb6l"/><path class="d6dm6ebtl"/><path class="t0ql0qb5i"/><path class="yyx7p_bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:intellicare-agora" {...props}></Icon>
<style>
:global(.d6dm6ebtl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m7.98 7.432l24.831 14.335l-17.624 10.174");
}

:global(.qp2wneb6l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.394 6.018a3.86 3.86 0 0 0-1.931 3.344v29.27c.001 2.973 3.22 4.83 5.794 3.345l25.348-14.634c2.576-1.487 2.576-5.205 0-6.692L13.257 6.017a3.86 3.86 0 0 0-3.863 0z");
}

:global(.t0ql0qb5i) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.025 22.063L15.188 36.401V16.053");
}

:global(.yyx7p_bnw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.326 42.5V13.823l17.623 10.174");
}

</style>
