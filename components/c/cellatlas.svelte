<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pg5i-6b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:cellatlas" {...props}></Icon>
<style>
:global(.pg5i-6b5x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.5 34.475l9.329-20.953l9.329 20.956M43.5 13.525l-9.329 20.953l-9.329-20.956");
}

</style>
