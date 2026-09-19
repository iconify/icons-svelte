<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t1olzru6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:komo" {...props}></Icon>
<style>
:global(.t1olzru6f) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.272 4.5v17.313L14.46 24l-2.188 2.187V43.5m23.456-39L16.647 24l19.081 19.5");
}

</style>
