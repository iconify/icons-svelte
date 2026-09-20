<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kvmtb5b3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:mobile-text-sharp" {...props}></Icon>
<style>
:global(.kvmtb5b3y) {
  fill: currentColor;
  d: path("M8.385 11.596h7.307v-1H8.385zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
