<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ugj4e4oev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:otter" {...props}></Icon>
<style>
:global(.ugj4e4oev) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.076 23.98a8.28 8.28 0 1 1-.004-.24m4.375-7.698l.09 15.916m6.654-15.916l.09 16.096m6.475-11.06l.09 5.935m6.474-8.003l.18 10.16");
}

</style>
