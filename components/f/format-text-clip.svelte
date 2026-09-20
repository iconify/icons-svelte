<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_m1ktm7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:format-text-clip" {...props}></Icon>
<style>
:global(.c_m1ktm7j) {
  fill: currentColor;
  d: path("M5.077 19.5v-15h1v15zm12.846 0v-7H8.846v-1h9.077v-7h1v15z");
}

</style>
