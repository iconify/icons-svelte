<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cfaq31bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:faders-horizontal-bold" {...props}></Icon>
<style>
:global(.cfaq31bow) {
  fill: currentColor;
  d: path("M176 80a12 12 0 0 1 12-12h28a12 12 0 0 1 0 24h-28a12 12 0 0 1-12-12M40 92h96v12a12 12 0 0 0 24 0V56a12 12 0 0 0-24 0v12H40a12 12 0 0 0 0 24m176 72h-92a12 12 0 0 0 0 24h92a12 12 0 0 0 0-24M84 140a12 12 0 0 0-12 12v12H40a12 12 0 0 0 0 24h32v12a12 12 0 0 0 24 0v-48a12 12 0 0 0-12-12");
}

</style>
