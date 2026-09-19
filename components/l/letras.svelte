<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="edd4hqb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:letras" {...props}></Icon>
<style>
:global(.edd4hqb4e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.989 18.074L21.279 5.5l7.979 10.26l12.977-.753l-7.29 10.76l4.733 12.107l-12.49-3.608L17.13 42.5l-.425-12.988l-10.94-7.014z");
}

</style>
