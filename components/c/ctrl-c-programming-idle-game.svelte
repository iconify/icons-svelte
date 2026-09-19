<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xe3yfqbww"/><path class="bvq6_bbjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ctrl-c-programming-idle-game" {...props}></Icon>
<style>
:global(.bvq6_bbjb) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.207 34.825H8.738V15.577l10.848.018l-.02-11.095h11.228v8.675M19.566 4.5L8.739 15.577");
}

:global(.xe3yfqbww) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.054 24.27l-.02-11.095H39.26V43.5H17.206V24.252Zm-.021-11.095L17.206 24.252");
}

</style>
