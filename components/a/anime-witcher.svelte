<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x_p78f8lx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:anime-witcher" {...props}></Icon>
<style>
:global(.x_p78f8lx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.187 13.079l-7.03 21.842l-7.031-21.842l-7.031 21.842l-7.031-21.842M4.5 20.221l39 11.871");
}

</style>
