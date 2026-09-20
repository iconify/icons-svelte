<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4bw96rjc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:destruction-sharp" {...props}></Icon>
<style>
:global(.m4bw96rjc) {
  fill: currentColor;
  d: path("M4 20.23v-6.442h16v6.443zm2.66-7.941l-3.622-2.1l5.096-.866l-1.393-5.048l4.263 3.044L13.6 2.77l.865 5.154l5.048-1.394l-3.025 4.263l2.647 1.496z");
}

</style>
