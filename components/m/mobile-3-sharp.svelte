<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zub62lhld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-3-sharp" {...props}></Icon>
<style>
:global(.zub62lhld) {
  fill: currentColor;
  d: path("M9.385 19.23h5.307v-1H9.385zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
