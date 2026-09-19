<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ov3bz7b4t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:microsoftbing-alt" {...props}></Icon>
<style>
:global(.ov3bz7b4t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.57 4.5l7.85 2.87l-.05 27.16l10.43-6.05l-5.2-2.8l-3.28-8.18l16.88 5.88l.23 9L18.37 43.5L10.65 39Z");
}

</style>
