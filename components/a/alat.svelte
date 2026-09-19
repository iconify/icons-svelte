<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="emx8qkbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:alat" {...props}></Icon>
<style>
:global(.emx8qkbxd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.49 11.859L43.5 36.141H32.521L24 21.39l-5.49-9.531L4.5 36.141h18.658");
}

</style>
