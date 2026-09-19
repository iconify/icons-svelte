<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="d5k9e5bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:a2" {...props}></Icon>
<style>
:global(.d5k9e5bal) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.579 36.142c-.041-4.789 1.062-8.746 7.08-8.497c8.587-21.882-26.423-21.048-17.09-.131c2.829-.176 7.52 1.509 6.719 9.146M42.5 33.479l-37 5.824m0-28.263l12.345 2.29m14.51 2.2L42.5 17.011");
}

:global(.ll0g54h-q) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

</style>
