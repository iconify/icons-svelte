<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="gqbfzc44u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:rectangle-landscape-32-light" {...props}></Icon>
<style>
:global(.gqbfzc44u) {
  fill: currentColor;
  d: path("M2 8.5A4.5 4.5 0 0 1 6.5 4h19A4.5 4.5 0 0 1 30 8.5v15a4.5 4.5 0 0 1-4.5 4.5h-19A4.5 4.5 0 0 1 2 23.5zM6.5 5A3.5 3.5 0 0 0 3 8.5v15A3.5 3.5 0 0 0 6.5 27h19a3.5 3.5 0 0 0 3.5-3.5v-15A3.5 3.5 0 0 0 25.5 5z");
}

</style>
