<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awujtcbza"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:movie-edit-sharp" {...props}></Icon>
<style>
:global(.awujtcbza) {
  fill: currentColor;
  d: path("M2 20V4h2l2 4h3L7 4h2l2 4h3l-2-4h2l2 4h3l-2-4h3q.825 0 1.413.588T22 6v1.1l-10 10V20zm12 1v-3.075l6.575-6.55l3.075 3.05L17.075 21zm6.575-5.6l.925-.975l-.925-.925l-.95.95z");
}

</style>
